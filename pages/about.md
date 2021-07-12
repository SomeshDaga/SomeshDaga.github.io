---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>

I'm a Software Engineer with a strong background in mobile robotics and manipulation. Through previous technical and leadership roles at a robotics startup, and through my master's study at the University of Waterloo, I bring to the table a great blend of practical and research experience.

From a practical perspective, I have developed a wide arsenal of skills from previous work in architecting and implementing core robotic algorithms, DevOps pipelines, Cloud and IoT solutions, UI/UX applications, Robot Behavior interfaces, and much more. Deep Reinforcement Learning has opened up new pathways for the advancement of intelligent agents, and my research experience has been focused on efficient and explainable learning of robotic manipulation using data-driven methods. 

In addition to robotics, I am also highly interested in the fields of algorithmic trading and diagnostic/surgical healthcare, and am seeking opportunities to contribute to any these domains.

<p class="text-center">
{% include elements/button.html link="/assets/resume.pdf" text="CV/Resume" size="lg" %}
</p>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

{% if site.timeline %}
<div class="row">
{% include about/timeline.html %}
</div>
{% endif %}
