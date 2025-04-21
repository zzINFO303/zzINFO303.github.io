---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
add text

<div class="row">
{% include about/skills.html title="Skills" source=site.data.skills show_progress=false show_level=false %}
{% include about/skills.html title="Awards" source=site.data.awards show_progress=false show_level=true %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
