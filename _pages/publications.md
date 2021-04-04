---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
---

An up-to-date list is available on [Google Scholar](https://scholar.google.es/citations?user=JlZbbzIAAAAJ&hl=es){:target='\_blank'}.

<div class="publications">

<h2 class="type">manuscripts & preprints</h2>
{% bibliography -f papers -q @*[typ=preprint]* %}

<h2 class="type">journal articles</h2>
{% bibliography -f papers -q @*[typ=journal]* %}

<h2 class="type">conferences</h2>
{% bibliography -f papers -q @*[typ=conference]* %}

<h2 class="type">book chapters</h2>
{% bibliography -f papers -q @*[typ=book]* %}

</div>
