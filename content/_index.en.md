---
title: ''
date: 2026-10-15
type: landing
sections:
  - block: hero
    content:
      announcement:
        badge:
          text: News
          color: green
        text: Three studies at IUMS 2026 in Lisbon.
        link:
          text: Read more
          url: news/2026-10-iums-2026-lisboa/
      eyebrow: Science outreach · FEIS-UNESP
      title: Fungi, soil and [science that reaches society]
      text: Research in mycology, plant pathology and soil microbiology from a One Health perspective, explained simply for farmers, students and anyone curious.
      primary_action:
        text: Explore the research
        url: research/
        icon: arrow-right
      secondary_action:
        text: About me
        url: about/
    design:
      background:
        gradient_mesh:
          enable: true
      size: compact
  - block: features
    content:
      title: What I study
      text: 'Four fronts with one common thread, One Health: the health of plants, people and the environment is connected.'
      subtitle: Research lines
      items:
        - name: Bioprospecting microorganisms
          description: Searching for microorganisms with potential to control plant pathogens.
          icon: magnifying-glass
        - name: Biomaterials against plant pathogenic fungi
          description: Red propolis and silver-based composites to control fungi such as *Fusarium verticillioides*.
          icon: shield-check
        - name: Mushroom-farming residues as bio-inputs
          description: Spent *Pleurotus ostreatus* substrate as a biofertilizer and substrate conditioner.
          icon: arrow-path
        - name: Beneficial microorganisms in crop production
          description: Bacteria such as *Bacillus* and mycorrhizal fungi for plant growth and seedling production.
          icon: beaker
    design:
      layout: grid
    id: linhas
  - block: collection
    content:
      title: Latest news
      count: 3
      archive:
        text: See all news
        enable: true
        link: news/
      filters:
        folders:
          - blog
    design:
      columns: 3
      show_read_time: false
      view: article-grid
    id: noticias
  - block: collection
    content:
      title: Featured publications
      archive:
        text: See all publications
        enable: true
        link: publications/
      filters:
        featured_only: true
        folders:
          - publications
    design:
      view: citation
    id: destaques
  - block: cta-card
    content:
      title: Science in your feed
      text: Behind the scenes in the lab, fun facts about fungi and research news, on Instagram.
      button:
        text: Follow
        url: https://linktr.ee/gfspesquisa
        icon: arrow-right
    design:
      card:
        text_color: light
summary: ''
---
