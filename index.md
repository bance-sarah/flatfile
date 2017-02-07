---
title: accueil
layout: default
---

<h1>{{page.title}}</h1>

This site aims to be a comprehensive guide to Jekyll. We’ll cover topics such as getting your site up and running, creating and managing your content, customizing the way your site works and looks, deploying to various environments, and give you some advice on participating in the future development of Jekyll itself.

<ul>
{% for cour in site.cours %}
<li><a href="{{ cour.url }}">{{ cour.title }}</a></li>
{% endfor %}
</ul>

<ul>
{% for product in site.products %}
<li><a href="{{ product.url }}">{{ product.title }}</a></li>
{% endfor %}
</ul>
