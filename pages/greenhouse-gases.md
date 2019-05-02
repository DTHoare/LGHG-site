---
layout: page-fullwidth
subheadline: "The Science"
title: "Greenhouse Gases"
teaser: "This is a bunch of information about the basic science."
header:
   title: "Greenhouse Gases"
   background-color: "#c7e8e8"
   image: "methane.png"
permalink: "/greenhouse-gases/"
---
<div class="row">
  <div class="small-6 columns">
    <img src="{{ site.urlimg }}/{{ page.header.image }}" alt="{{ site.title }}">
  </div>
  <div class="small-6 columns">
    <h3>Methane</h3>
    <p> Some info about Ch4 </p>
  </div><!-- /.small-12.columns -->
</div><!-- /.row -->
<hr>
<div class="row">
  <div class="small-6 columns">
    <h3>Carbon Dioxide</h3>
    <p> Some info about Co2 </p>
  </div>
  <div class="small-6 columns">
    Image for CO2
  </div><!-- /.small-12.columns -->
</div><!-- /.row -->


<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
