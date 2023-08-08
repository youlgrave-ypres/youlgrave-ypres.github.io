{% assign atopics = site[include.collection] %}
{% for atopic in atopics %}
  - [{{ atopic.title }}]({{ atopic.url }})
{% endfor %}