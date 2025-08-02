---
layout: default
title: Blog của Kien Alang
lang: vi
---

# Chào mừng!

Chào mừng đến với blog của Kien Alang, nơi mình viết những thứ linh tinh từ những gì mình học được.

## Blog Posts

{% assign all_categories = site.pages | map: "category" | compact | uniq | sort %}
{% for category in all_categories %}
  {% assign category_name = category | replace: "-", " " | capitalize %}
  
### {{ category_name }}
  {% assign category_posts = site.pages | where: "category", category | sort: "date" | reverse %}
  {% for post in category_posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) - *{{ post.date | date: "%B %d, %Y" }}*
  {% endfor %}
{% endfor %}

## Về blog này

Đây là nơi mình chia sẻ những suy nghĩ và kiến thức từ việc học hỏi hàng ngày.
