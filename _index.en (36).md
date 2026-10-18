---
# Home page (English). Sections appear in the order below.
title: ''
summary: ''
date: 2026-10-15
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: See publications
        url: publications/
      headings:
        about: 'About me'
        education: 'Education'
        interests: 'Interests'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🔬 Research lines'
      subtitle: ''
      text: |-
        - **Circular economy with mushrooms** — the substrate left over from *Pleurotus ostreatus* cultivation as a source of nutrients for plants.
        - **Natural control of fungi** — natural compounds, such as red propolis, and nanomaterials against fungi that attack maize and fungi of clinical importance.
        - **Microbial bio-inputs** — bacteria such as *Azospirillum* and *Bacillus* supporting plant growth.
        - **Stingless bees** — characterization of jataí honey (*Tetragonisca angustula*).

        [Explore the projects →](research/)
    design:
      columns: '1'

  - block: collection
    id: destaques
    content:
      title: Featured publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
      show_read_time: false

  - block: collection
    content:
      title: Recent publications
      text: ''
      count: 5
      filters:
        folders:
          - publications
        exclude_featured: false
      archive:
        enable: true
        text: See all publications
        link: publications/
    design:
      view: citation

  - block: collection
    id: noticias
    content:
      title: News
      count: 3
      filters:
        folders:
          - blog
      archive:
        enable: true
        text: See all news
        link: news/
    design:
      view: card
      show_read_time: false
---
