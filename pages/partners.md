---
layout: page
subheadline: "The People behind the Project"
title: "Partnerships"
teaser: "This is a summary of the people and organisations."
header:
   title: "Project Partners"
   background-color: "#c7e8e8"
   image: "london.png"
permalink: "/partners/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
