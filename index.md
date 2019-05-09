---
title: I Want To Support
exclude: true

---
# I Want To Support

So you want to support open source projects by donating money, but you don't know how? Check the projects below for more information on how to support them.

{% for page in site.html_pages %}
  {% unless page.exclude %}
[ {{ page.title }} - {{page.name}} ]( {{ page.url }} )
  {% endunless %}
{% endfor %}
