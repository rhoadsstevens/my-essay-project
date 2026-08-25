---
title: My First Essay
order: 1
---

## Introduction

This is my first essay using CB-Essay! I can write in **Markdown** and include [links](https://example.com).

### Adding Features

I can add blockquotes:

{% include essay/feature/blockquote.html
   quote="Knowledge comes, but wisdom lingers"
   speaker="Alfred Lord Tennyson" %}

And margin notes:{% include essay/feature/aside.html text="This is a margin note!" %}

{% include essay/feature/aside.html
   objectid="coll004"
   text="These are very nice crows" %}

   {% include essay/feature/image-gallery.html
   objectid="crows_01;crows_02;crows_03" %}
