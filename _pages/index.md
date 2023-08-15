---
layout: defaults/page
permalink: index.html
narrow: true
title: "👋 Hoi daar! Ik ben Marc."
---

Hoi ik ben Marc en kom uit het noorden van het land. Al van kleins af aan prutste ik met computers en website’s.

In 2003 ben ik met de mijn eerste weblog begonnen. Eerst gewoon over mijn dagelijks belevenissen maar later ook over mijn hobby’s.

Na een paar jaar begon een andere hobby van mij meer aandacht te trekken en stopte ik met bloggen. Maar nu in 2021 ben ik weer 
begonnen met het bloggen over van alles en nog wat mij interesseert.

## What is it?

{% include components/intro.md %}

[Here's the full feature list and some quick examples of what it can do.]({{ site.baseurl}}{% link _pages/about.md %})

## How to use it

This web site is the documentation for the theme and also provides examples of how you can use and modify it. TIt is built using Friday Theme directly from the [GitHub repo](https://github.com/sfreytag/friday-theme) and published to GitHub pages.

[The documentation]({{ site.baseurl }}{% link list/projects.md %}) covers the basics of installing and using it, and is an example of how you could write documentation about your own projects.

[The blog]({{ site.baseurl }}{% link list/posts.html %}) has a bunch of tips about how to use Friday Theme. These show how the blog works, including the tags. There's the three most-recent posts below included below.

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


