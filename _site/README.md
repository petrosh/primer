# primer
Primer http://primercss.io/ install. Repo: https://github.com/primer/primer.

#### Notes

* `node v0.12.7`
* `npm v2.11.3`
* `bower v1.4.1`
* `Sass v3.4.13`

```bash
pico .gitignore
sudo npm install -g bower
bower install primer-css --save
gem install rouge
```

Add `_syntax.css`

### CSS

Compile with `scss -w css/style.scss`
For fixed `masthead`:

```css
body {
  margin-top: 89px;
}
.masthead {
  position: fixed;
  right: 0;
  left: 0;
  top: 0;
}
```

### Deployment

```sh
$git branch -D gh-pages
Deleted branch gh-pages (was 7f93c5e).
$git checkout -b gh-pages
Switched to a new branch 'gh-pages'
$git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.
$git subtree push --prefix _site origin gh-pages
git push using:  origin gh-pages
-n 1/      21 (0)
-n 2/      21 (1)
-n 3/      21 (2)
-n 4/      21 (3)
-n 5/      21 (4)
-n 6/      21 (5)
-n 7/      21 (6)
-n 8/      21 (7)
-n 9/      21 (8)
-n 10/      21 (9)
-n 11/      21 (10)
-n 12/      21 (11)
-n 13/      21 (12)
-n 14/      21 (13)
-n 15/      21 (14)
-n 16/      21 (15)
-n 17/      21 (16)
-n 18/      21 (17)
-n 19/      21 (18)
-n 20/      21 (19)
-n 21/      21 (20)
Counting objects: 1, done.
Writing objects: 100% (1/1), 165 bytes | 0 bytes/s, done.
Total 1 (delta 0), reused 0 (delta 0)
To https://github.com/petrosh/primer.git
 * [new branch]      22056d8868a1abd4d3fa21d36bcb64df99eeb6e9 -> gh-pages
```
