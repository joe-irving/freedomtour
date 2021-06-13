---
layout: map
title: Map
---
# Map

Below is the map of all locations the tour will go through:

<ul>
{% for point in site.route %}
{% if point.Location and point.Location != '' %}
<li>{{ point.Location | strip }}</li>
{% endif %}
{% endfor  %}
</ul>
