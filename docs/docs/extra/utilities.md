---
layout: doc
title: Utilities
categories: extra
permalink: /docs/extra/utilities/
---

<p>Kissui has a number of small utility classes that act as easy-to-use helpers. Sometimes it's better to use a utility class than create a whole new class just to float an element.</p>


<pre class="code-example">
<code class="language-css">/* Utility Classes */

/* Make element full width */
.u-full-width {
  width: 100%;
  box-sizing: border-box; 
}

/* Make sure elements don't run outside containers (great for images in columns) */
.u-max-full-width {
  max-width: 100%;
  box-sizing: border-box; 
}

/* Float either direction */
.u-pull-right {
  float: right; 
}
.u-pull-left {
  float: left; 
}

/* Clear a float */
.u-cf {
  content: "";
  display: table;
  clear: both; 
}
</code>
</pre>
