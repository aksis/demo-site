---
layout: page
title: Blog
permalink: /blog/
---

<!-- Layout {{ layout.layout }}, page layout {{ page.layout }}, page name {{ page.name }} & path {{ page.path }} -->

{%- for post in site.posts -%}

### [{{ post.title | escape }}]({{ post.url | relative_url }})

{%- endfor -%}
