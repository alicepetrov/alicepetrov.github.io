---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

<style>
  /* Hide the original BibBase group name text */
  #group_article div.bibbase_group i+span,
  #group_inproceedings div.bibbase_group i+span,
  #group_mastersthesis div.bibbase_group i+span,
  #group_phdthesis div.bibbase_group i+span,
  #group_techreport div.bibbase_group i+span,
  #group_unpublished div.bibbase_group i+span,
  #group_incollection div.bibbase_group i+span {
    display: none;
  }

  /* Define the new group name text */
  #group_article div.bibbase_group i:after { content: "Journal Articles" }
  #group_inproceedings div.bibbase_group i:after { content: "Conference and Workshop Publications" }
  #group_mastersthesis div.bibbase_group i:after { content: "Master's Thesis" }
  #group_phdthesis div.bibbase_group i:after { content: "PhD Thesis" }
  #group_techreport div.bibbase_group i:after { content: "Technical Report" }
  #group_unpublished div.bibbase_group i:after { content: "Unpublished" }
  #group_incollection div.bibbase_group i:after { content: "In Collection" }

  /* Style the new group names to have italic, non-bold headings */
  div.bibbase_group > i:after {
    font-family: sans-serif;
    font-style: italic;
    font-weight: normal;
    font-size: 1.2rem;
    color: #333333;
  }
</style>

<script src="https://bibbase.org/show?bib=https://raw.githubusercontent.com/alicepetrov/alicepetrov.github.io/main/_bibliography/papers.bib&jsonp=1&theme=simple"></script>

<noscript>
  <p>Please enable JavaScript to see publications.</p>
</noscript>
