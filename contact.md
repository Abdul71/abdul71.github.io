---
layout: default
is_contact: true
title: "./abdul71/contact"
---

## Contact

<i class="far fa-envelope"></i> Email: [aabdelka[at]u.rochester.com](mailto:aabdelka@u.rochester.edu)

### Social

{% for entry in site.social %}
<a href="{{ entry.url }}" target="_blank"><i class="{{ entry.icon }}"></i> {{ entry.name }}</a>
{% endfor %}

### Academic

{% for entry in site.academic %}
<a href="{{ entry.url }}" target="_blank"><i class="{{ entry.icon }}"></i> {{ entry.name }}</a>
{% endfor %}
