---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

### Research interests

- Geometric & topological methods for ML
- Invariant/equivariant models and discrete differential operators
- Robust representation learning on non-Euclidean domains (meshes, manifolds, graphs)
- Applications: scientific computing, vision/graphics, and data-driven PDEs

### Current directions

- **Topology-aware learning pipelines** that use persistent/intersection homology to guide architecture and regularization.
- **Structure-preserving operators** for meshes and point clouds (discrete exterior calculus; spectral methods).
- **Data with singularities**: detecting, characterizing, and leveraging singular structure in high-dimensional data.

<style>
  /* Scope all fixes to the BibBase area */
  #bibbase {
    /* nothing here; just a scope anchor */
  }

  /* 1) Hide any <hr> BibBase adds (horizontal bars) */
  #bibbase hr,
  #bibbase .bibbase_group > hr,
  #bibbase .bibbase_paper > hr {
    display: none !important;
  }

  /* 2) Remove vertical borders some themes put on lists/blocks */
  #bibbase .bibbase_group,
  #bibbase .bibbase_paper,
  #bibbase li,
  #bibbase ul,
  #bibbase ol,
  #bibbase blockquote {
    border: 0 !important;
    box-shadow: none !important;
  }

  /* 3) Kill common left-border styles (e.g., blockquotes / timelines) */
  #bibbase blockquote {
    border-left: 0 !important;
    padding-left: 0 !important;
    margin-left: 0 !important;
  }

  /* 4) Nuke decorative pseudo-elements that can render as vertical lines */
  #bibbase .bibbase_group::before,
  #bibbase .bibbase_group::after,
  #bibbase .bibbase_paper::before,
  #bibbase .bibbase_paper::after,
  #bibbase li::before {
    content: none !important;
    display: none !important;
  }
</style>

<!-- Give BibBase a dedicated container so the CSS above applies reliably -->
<div id="bibbase"></div>
<script src="https://bibbase.org/show?bib=https://raw.githubusercontent.com/alicepetrov/alicepetrov.github.io/main/_bibliography/papers.bib&jsonp=1"></script>

<noscript>
  <p>Please enable JavaScript to see publications.</p>
</noscript>
