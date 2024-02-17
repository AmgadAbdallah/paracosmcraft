---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2023, 2024]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Conference papers
{% bibliography --query @confarticle %}
</div>

<div class="jumbotron">
### Journal articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Submitted for publication
{% bibliography --query @inproceedings %}
</div>
