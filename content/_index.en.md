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
      text: Research in mycology, soil microbiology and bio-inputs, explained simply for farmers, students and anyone curious.
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
      text: 'Four fronts, one shared goal: farming that relies less on chemicals and makes better use of what nature offers.'
      subtitle: Research lines
      items:
        - name: Circular economy with mushrooms
          description: The substrate left over from *Pleurotus ostreatus* cultivation becomes a source of nutrients for plants.
          icon: arrow-path
        - name: Natural control of fungi
          description: Red propolis and nanomaterials against fungi that attack maize and fungi of clinical importance.
          icon: shield-check
        - name: Microbial bio-inputs
          description: Bacteria such as *Azospirillum* and *Bacillus* supporting plant growth.
          icon: beaker
        - name: Stingless bees
          description: Characterizing jataí honey (*Tetragonisca angustula*).
          icon: bug-ant
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
