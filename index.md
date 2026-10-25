---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
image: "/assets/thumbnails/site.jpeg"

---

{% for post in site.posts %}
  [![{{ post.title }}]({{ post.image }})]({{ post.url }})
  [{{ post.title }}]({{ post.url }})
{% endfor %}
