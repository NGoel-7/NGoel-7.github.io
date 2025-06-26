---
layout: default
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
This is where can read a little more about <mark> me </mark>. ** I am definitely a very interesting person with a quintillion interests**.
Or I could show off some **Skills** and write a bit more about things that make me more employable, like *leadership* and *teamwork*

<div class="row">
{% include about/skills.html title="Programming Languages" source=site.data.programming-skills %}
{% include about/skills.html title="Hardware Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>