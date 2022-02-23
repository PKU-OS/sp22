---
layout: page
title: Schedule
nav_order: 1
currWeekNumber: 1
---

# {{ site.tagline }}
{: .mb-2 }
Peking University, 2022 Spring
{: .mb-0 .fs-6 .text-grey-dk-000 }

<img src="/sp22/assets/images/pkuos.svg">

<p>
<a href="https://alfredthiel.gitbook.io/pintosbook/" class="btn btn-purple">Project Gitbook</a>
<a href="https://course.pku.edu.cn" class="btn btn-green">PKU Course Website</a>
</p>

{% if site.announcements %}
{{ site.announcements.last }}
[Previous Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## Schedule
{% for module in site.modules %}
<a name="week-{{module.weekNumber}}"></a>
{{ module }}
{% endfor %}
