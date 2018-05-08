---
layout: page
---

{% for post in site.categories[page.category] %}
    [{{ post.title }}]({{ post.url | absolute_url }})
{% endfor %}