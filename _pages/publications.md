---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>First-author</h2>
{% bibliography --query @*[keywords~=firstauthor] %}

<h2>Collaboration</h2>
{% bibliography --query @*[keywords~=collaboration] %}

</div>
