---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hi I am **{{ site.author.name }}**!!<br>


<p class="text-center">
{% include elements/button.html link="/assets/cv_public.pdf" text="CV" size="lg" %}
</p>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
<!-- {% include about/skills.html title="Other Skills" source=site.data.other-skills %} -->
</div>