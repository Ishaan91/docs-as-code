---
var: variable
replace: replaced_variable
title: Page_title
layout: demo
---

# some stuff
## {{ page.title }}

Home page for the Github pages.

Some change for TWT session activity.

Some more changes made in the local.

## Local variables
{{ page.var }}
{{ page.replace }}

The following games are one of the best games I've played:

{% for item in site.data.demo %}

Protagonist: {{ item.name }}\
Genre: {{ item.genre }}\
Developer: {{ item.dev }}

{% endfor %}		

[test file](docs-as-code/test/testfile2.md)