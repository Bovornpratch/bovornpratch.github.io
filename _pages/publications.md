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
<h3> Full Publication list can be found  <a href='https://ui.adsabs.harvard.edu/search/filter_doctype_facet_hier_fq_doctype=AND&
filter_doctype_facet_hier_fq_doctype=doctype_facet_hier%3A%220%2FArticle%22&fq=%7B!type%3Daqp%20v%3D%24fq_doctype%7D&fq_doctype=(doctype_facet_hier%3A%220%2FArticle%22)&q=author%3A%22Vijarnwannaluk%2C%20Bovornpratch%22&sort=date%20desc%2C%20bibcode%20desc&p_=0'> here. </a> </h3>

<h3> First Author Publications </h3>
{% bibliography -f papers %}

<h3> Co-I Publications </h3>
{% bibliography -f papers_coi %}


</div>
