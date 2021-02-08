---
title: My favourite video games
layout: demo
---

# {{ page.title }}

The following list comprises of a few of the best video games I've played. These are a must to try if you haven't already. Video games are awesome.\
Please note that the list is iteratively generated. I'm working on creating pages for each entry.

{% for item in site.data.demo %}

Game: [ {{ item.name}} ]({{ item.file }})\
Genre: {{ item.genre }}\
Developer: {{ item.dev }}

{% endfor %}		

	