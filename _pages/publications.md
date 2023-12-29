---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

<h1>Journal Publications</h1>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[category=journal] %}

<h1>Conference Publications</h1>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[category=conference] %}

<h1>Theses</h1>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[category=thesis] %}

<h1>Workshop, Extended Abstract and Demo Publications</h1>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[category=workshop] %}

<h1>Preprints</h1>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[category=preprint] %}

</div>
