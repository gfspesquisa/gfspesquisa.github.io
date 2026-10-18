---
# Página inicial. As seções aparecem na ordem abaixo.
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
        text: Ver publicações
        url: publicacoes/
      headings:
        about: 'Sobre mim'
        education: 'Formação'
        interests: 'Interesses'
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
      title: '🔬 Linhas de pesquisa'
      subtitle: ''
      text: |-
        - **Economia circular com cogumelos** — o substrato que sobra do cultivo de *Pleurotus ostreatus* como fonte de nutrientes para as plantas.
        - **Controle natural de fungos** — compostos naturais, como a própolis vermelha, e nanomateriais contra fungos que atacam o milho e fungos de importância clínica.
        - **Bioinsumos microbianos** — bactérias como *Azospirillum* e *Bacillus* a serviço do crescimento das plantas.
        - **Abelhas sem ferrão** — caracterização do mel de jataí (*Tetragonisca angustula*).

        [Conheça os projetos →](pesquisa/)
    design:
      columns: '1'

  - block: collection
    id: destaques
    content:
      title: Publicações em destaque
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
      title: Publicações recentes
      text: ''
      count: 5
      filters:
        folders:
          - publications
        exclude_featured: false
      archive:
        enable: true
        text: Ver todas as publicações
        link: publicacoes/
    design:
      view: citation

  - block: collection
    id: noticias
    content:
      title: Notícias
      count: 3
      filters:
        folders:
          - blog
      archive:
        enable: true
        text: Ver todas as notícias
        link: noticias/
    design:
      view: card
      show_read_time: false
---
