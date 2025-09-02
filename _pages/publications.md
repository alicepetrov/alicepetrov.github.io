---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

<style>
  /* Scope all fixes to the BibBase area */
  #bibbase { }

  /* 1) Hide BibBase HRs (horizontal separators) just in case */
  #bibbase hr,
  #bibbase .bibbase_group > hr,
  #bibbase .bibbase_paper > hr {
    display: none !important;
  }

  /* 2) Remove vertical "timeline" bars the theme adds to year/group headings */
  #bibbase .year,
  #bibbase h1.year, #bibbase h2.year, #bibbase h3.year, #bibbase h4.year, #bibbase h5.year, #bibbase h6.year,
  #bibbase .bibbase_group > h1, #bibbase .bibbase_group > h2, #bibbase .bibbase_group > h3,
  #bibbase .bibbase_group > h4, #bibbase .bibbase_group > h5, #bibbase .bibbase_group > h6 {
    border: 0 !important;
    box-shadow: none !important;
    position: static !important;
  }

  #bibbase .year::before,  #bibbase .year::after,
  #bibbase h1.year::before, #bibbase h1.year::after,
  #bibbase h2.year::before, #bibbase h2.year::after,
  #bibbase h3.year::before, #bibbase h3.year::after,
  #bibbase h4.year::before, #bibbase h4.year::after,
  #bibbase h5.year::before, #bibbase h5.year::after,
  #bibbase h6.year::before, #bibbase h6.year::after,
  #bibbase .bibbase_group > h1::before, #bibbase .bibbase_group > h1::after,
  #bibbase .bibbase_group > h2::before, #bibbase .bibbase_group > h2::after,
  #bibbase .bibbase_group > h3::before, #bibbase .bibbase_group > h3::after,
  #bibbase .bibbase_group > h4::before, #bibbase .bibbase_group > h4::after,
  #bibbase .bibbase_group > h5::before, #bibbase .bibbase_group > h5::after,
  #bibbase .bibbase_group > h6::before, #bibbase .bibbase_group > h6::after {
    content: none !important;
    display: none !important;
  }

  /* 3) Extra safety: some themes add a vertical rule via a parent "timeline" container */
  #bibbase .timeline,
  #bibbase .timeline::before,
  #bibbase .bibbase_group::before,
  #bibbase .bibbase_group::after {
    content: none !important;
    display: none !important;
    border: 0 !important;
    box-shadow: none !important;
  }
</style>

<!-- Give BibBase a dedicated container so the CSS above applies reliably -->
<div id="bibbase">
<script src="https://bibbase.org/show?bib=https://raw.githubusercontent.com/alicepetrov/alicepetrov.github.io/main/_bibliography/papers.bib&jsonp=1"></script>
</div>

<noscript>
  <p>Please enable JavaScript to see publications.</p>
</noscript>
