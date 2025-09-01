---
layout: post
title: "Second Test Post"
date: Mon, 01 Sep 2025 10:03:48
categories: TEST TESTING
tags: test testing tested
---

What happens when post stop being nice and get real?
I don't know either, and we probably wont' find out tody

## Well what is it then?
How should I know.  I'm just making this up as I go along

### Related Content

{% for tag in site.tags %}
{% assign t = tag | first %}
{% assign posts = tag | last %}
{% if page.tags contains t %}
{{ t }}
{{ posts }}
{% endif %}


{% endfor %}

