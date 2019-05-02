---
layout: page-fullwidth
subheadline: "Our Goals"
title: "The London Greenhouse Gas Project"
teaser: "This is a summary of the project."
header:
   title: "About LGHG"
   background-color: "#c7e8e8"
   image: "london.png"
permalink: "/about/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
