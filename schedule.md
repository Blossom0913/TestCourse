---
layout: page
nav_exclude: true
description: The weekly event schedule.
---

# 课时安排

### 2023年秋季，第1周至第18周

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}