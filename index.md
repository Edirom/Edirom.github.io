---
layout: default
title: Welcome
---

# Welcome to Edirom Github Pages

This site offers you help and orientation when working in the context of digital music editions published with [Edirom Online](https://edirom.github.io/Edirom-Online/).

Setting up an _Edirom Online_ for your project is but one streak in publishing your digital edition, preparing your data and getting it into the right formats is where a huge amount of work has to be done. In order to assist you in achieving this we offer you an overview of the object types known to _Edirom Online_  and some overview of available tools and strategies to get your data where it belongs.

## Edirom Objects

{% for edirom-object in site.edirom-objects %}
* [{{ edirom-object.title }}]({{edirom-object.url}})
{% endfor %}
