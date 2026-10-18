---
# Home page (English). Sections appear in the order below.
# The personal introduction (photo, bio, education) is on the "About" page.
title: ''
summary: ''
date: 2026-10-15
type: landing

sections:
  - block: hero
    content:
      announcement:
        badge:
          text: News
          color: green
        text: I will present two studies at IUMS 2026 in Lisbon.
        link:
          text: Read more
          url: news/2026-10-iums-2026-lisboa/
      eyebrow: Science outreach · FEIS-UNESP
      title: Fungi, soil and [science that reaches the field]
      text: Research in mycology, soil microbiology and bio-inputs, explained simply for farmers, students and anyone curious.
      primary_action:
        text: Explore the research
        url: research/
        icon: arrow-right
      secondary_action:
        text: About me
        url: about/
    design:
      size: compact
      background:
        gradient_mesh:
          enable: true

  - block: features
    id: linhas
    content:
      subtitle: Research lines
      title: What I study
      text: 'Four fronts, one shared goal: farming that relies less on chemicals and makes better use of what nature offers.'
      items:
        - name: Circular economy with mushrooms
          icon: arrow-path
          description: The substrate left over from *Pleurotus ostreatus* cultivation becomes a source of nutrients for plants.
        - name: Natural control of fungi
          icon: shield-check
          description: Red propolis and nanomaterials against fungi that attack maize and fungi of clinical importance.
        - name: Microbial bio-inputs
          icon: beaker
          description: Bacteria such as *Azospirillum* and *Bacillus* supporting plant growth.
        - name: Stingless bees
          icon: bug-ant
          description: Characterizing jataí honey (*Tetragonisca angustula*).

    design:
      layout: grid

  - block: collection
    id: noticias
    content:
      title: Latest news
      count: 3
      filters:
        folders:
          - blog
      archive:
        enable: true
        text: See all news
        link: news/
    design:
      view: article-grid
      columns: 3
      show_read_time: false

  - block: collection
    id: destaques
    content:
      title: Featured publications
      filters:
        folders:
          - publications
        featured_only: true
      archive:
        enable: true
        text: See all publications
        link: publications/
    design:
      view: citation

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
---
