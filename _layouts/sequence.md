---
layout: page
---
<ul class="menu-list">
{% include collection_list.html collection=page.collection %}
</ul>

{{ content }}

{% include previous_next.html %}