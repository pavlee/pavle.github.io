---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
a fullstack developer with experience developing in Java frameworks like Spring Boot, Java Enterprise Stack and NodeJS, mostly in combination with VueJS and React.

<div class="row">
{% include about/skills.html title="Programming Languages" source=site.data.programming-skills %}
{% include about/skills.html title="Frameworks" source=site.data.framework-skills %}
</div>


<div class="row">
{% include about/skills.html title="Automation and Deployment" source=site.data.automation-skills %}
{% include about/skills.html title="Tools" source=site.data.tools-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
