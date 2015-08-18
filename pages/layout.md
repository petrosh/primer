---
layout: page
title: Layout
permalink: /layout/
---

Primer's layout includes basic page containers and a single-tiered, fraction-based grid system. That sounds more complicated than it really is though—it's just containers, rows, and columns.

You can find all the below styles in `_layout.scss`.

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

### Container

Center your page's contents with a `.container`.

{% highlight html %}
<div class="container">
  <!-- contents here -->
</div>
{% endhighlight %}

## Example

{% example html %}
<div class="container">
  <div class="columns">
    <div class="one-fifth column">
      .one-fifth
    </div>
    <div class="four-fifths column">
      .four-fifths
    </div>
  </div>

  <div class="columns">
    <div class="one-fourth column">
      .one-fourth
    </div>
    <div class="three-fourths column">
      .three-fourths
    </div>
  </div>

  <div class="columns">
    <div class="one-third column">
      .one-third
    </div>
    <div class="two-thirds column">
      .two-thirds
    </div>
  </div>

  <div class="columns">
    <div class="one-half column">
      .one-half
    </div>
    <div class="one-half column">
      .one-half
    </div>
  </div>
</div>
{% endexample %}
