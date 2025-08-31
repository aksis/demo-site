---
layout: page
title: Blog
permalink: /blog/
---

<!-- Layout {{ layout.layout }}, page layout {{ page.layout }}, page name {{ page.name }} & path {{ page.path }} -->

{%- for post in site.posts -%}
<a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
{%- endfor -%}
