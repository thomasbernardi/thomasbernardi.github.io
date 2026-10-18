---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: og
---

{% for post in site.posts %}
  [![{{ post.title }}]({{ post.thumbnail }})]({{ post.url }})
  [{{ post.title }}]({{ post.url }})
{% endfor %}
