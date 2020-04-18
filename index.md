---
layout: default
title: Home
---
# AI for Social Good at IJCAI 2020

Artificial intelligence is poised to play an increasingly large role in societies across the world. Accordingly, there is a growing interest in ensuring that AI is used in a responsible and beneficial manner. A range of perspectives and contributions are needed, spanning the full spectrum from fundamental research to sustained deployments.

This workshop will explore how artificial intelligence can contribute to solving social problems. For example, what role can AI play in promoting health, access to opportunity, and sustainable development? How can AI initiatives be deployed in an ethical, inclusive, and accountable manner? To address such questions, this workshop will bring together researchers and practitioners across artificial intelligence and a range of application domains. The objective is to share the current state of research and practice, explore directions for future work, and create opportunities for collaboration. 

Such questions are particularly salient in light of the COVID-19 pandemic. AI has an important role to play in providing insight into the course of the epidemic and developing targeted responses; we encourage submissions from both AI researchers as well as epidemiologists, health policy researchers, and other domain experts who are interested in engaging with the AI community.   

The workshop will be held in conjunction with the 28th International Joint Conference on Artificial Intelligence (IJCAI-20). The workshop will be entirely virtual.






<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>


