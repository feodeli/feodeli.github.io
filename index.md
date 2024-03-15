---
layout: default.liquid
title: Fernanda Odeli - Personal Trainer
---

<div class="links">
{% for link in site.data.links %}
* [{{ link.text }}]({{ link.href }})
{% endfor %}
</div>
