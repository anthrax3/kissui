---
layout: doc
title: Grid
categories: basics
permalink: /docs/basics/grid/
---

<p>The grid is a <u>12-column fluid grid with a max width of 960px</u>, that shrinks with the browser/device at smaller sizes. The max width can be changed with one line of CSS and all columns will resize accordingly. The syntax is simple and it makes coding responsive much easier. Go ahead, resize the browser. </p>

<div class="example-grid docs-example">
<div class="row">
  <div class="one column">One</div>
  <div class="eleven columns">Eleven</div>
</div>
<div class="row">
  <div class="two columns">Two</div>
  <div class="ten columns">Ten</div>
</div>
<div class="row">
  <div class="three columns">Three</div>
  <div class="nine columns">Nine</div>
</div>
<div class="row">
  <div class="four columns">Four</div>
  <div class="eight columns">Eight</div>
</div>
<div class="row">
  <div class="five columns">Five</div>
  <div class="seven columns">Seven</div>
</div>
<div class="row">
  <div class="six columns">Six</div>
  <div class="six columns">Six</div>
</div>
<div class="row">
  <div class="seven columns">Seven</div>
  <div class="five columns">Five</div>
</div>
<div class="row">
  <div class="eight columns">Eight</div>
  <div class="four  columns">Four</div>
</div>
<div class="row">
  <div class="nine columns">Nine</div>
  <div class="three columns">Three</div>
</div>
<div class="row">
  <div class="ten columns">Ten</div>
  <div class="two columns">Two</div>
</div>
<div class="row">
  <div class="eleven columns">Eleven</div>
  <div class="one column">One</div>
</div>
</div>


<!-- CODE EXAMPLE ———————————————————————————————————————— -->
<pre>
<code class="language-html">&lt;!-- .container is main centered wrapper --&gt;
&lt;div class="container"&gt;
  &lt;!-- columns should be the immediate child of a .row --&gt;
  &lt;div class="row"&gt;
    &lt;div class="one column"&gt;One&lt;/div&gt;
    &lt;div class="eleven columns"&gt;Eleven&lt;/div&gt;
  &lt;/div&gt;

  &lt;!-- just use a number and class 'column' or 'columns' --&gt;
  &lt;div class="row"&gt;
    &lt;div class="two columns"&gt;Two&lt;/div&gt;
    &lt;div class="ten columns"&gt;Ten&lt;/div&gt;
  &lt;/div&gt;

  &lt;!-- there are a few shorthand columns widths as well --&gt;
  &lt;div class="row"&gt;
    &lt;div class="one-third column"&gt;1/3&lt;/div&gt;
    &lt;div class="two-thirds column"&gt;2/3&lt;/div&gt;
  &lt;/div&gt;
  &lt;div class="row"&gt;
    &lt;div class="one-half column"&gt;1/2&lt;/div&gt;
    &lt;div class="one-half column"&gt;1/2&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code>
</pre>

<b>Note:</b> columns can be nested, but it's not recommended since the grid has <code>%-based</code> gutters, meaning a nested grid results in variable with gutters (which can end up being <b>really</b> small on certain browser/device sizes)

