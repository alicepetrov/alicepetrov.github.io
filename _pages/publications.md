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

  /* FIX 1: Style the new group names to have italic, non-bold headings */
  div.bibbase_group > i:after {
    font-family: sans-serif; /* Use a standard font */
    font-style: italic;     /* Set the style to italic */
    font-weight: normal;     /* Set the weight to normal (non-bold) */
    font-size: 1.2rem;       /* Make the font size appropriate for a heading */
    color: #333333;          /* Set a standard text color */
  }

  /* FIX 2: Remove rendered separators (borders or pseudo-elements) */
  .bibbase_entry span {
    /* Aggressively remove borders and spacing from any span inside an entry */
    border: none !important;
    padding-left: 0 !important;
    margin-left: 0 !important;
  }
  .bibbase_entry span::before,
  .bibbase_entry span::after {
    /* Aggressively hide any pseudo-elements that might be rendering the bar */
    display: none !important;
    content: none !important;
  }

</style>

<script src="https://bibbase.org/show?bib=https://raw.githubusercontent.com/alicepetrov/alicepetrov.github.io/main/_bibliography/papers.bib&jsonp=1"></script>

<noscript>
  <p>Please enable JavaScript to see publications.</p>
</noscript>
