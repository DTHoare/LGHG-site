---
layout: page
subheadline: "The Technology"
title: "Instruments"
teaser: "This is a summary of the kit."
header:
   title: "Instruments"
   background-color: "#c7e8e8"
   image: "instrument.png"
permalink: "/instruments/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
