---
layout: page
title: /about
permalink: /about/
---

![me](/images/me.jpg "Me")

### Who am I?

I am Joe Mizzi: software engineer, punk, nerd, musician, husband and the cook of my household. I work [Casechek](https://casechek.com), a healthcare company based in Chicago, IL, where I am the Director of Engineering. I play in a band called [The Mizzerables](https://themizzerables.bandcamp.com) and also with the [Klingon Pop Warrior](https://www.klingonpopwarrior.com). I like to evangelize on software development, music, restaurants and most all of my interests. I enjoy reading books by Martin Fowler and Uncle Bob. I intend to use this site to talk about the things I like and maybe provide something of value from time to time.

You can find me at:
{% for social_link in site.social_links %}
- <i style="width: 1em" class="fa fa-{{ social_link.font_awesome }}"></i> [{{ social_link.name }}({{ social_link.username }})]({{ social_link.link }}){:target="_blank"}
{%- endfor -%}