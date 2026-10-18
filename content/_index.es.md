---
# Página de inicio (español). Las secciones aparecen en el orden siguiente.
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
        text: Ver publicaciones
        url: publicaciones/
      headings:
        about: 'Sobre mí'
        education: 'Formación'
        interests: 'Intereses'
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
      title: '🔬 Líneas de investigación'
      subtitle: ''
      text: |-
        - **Economía circular con hongos comestibles** — el sustrato que queda del cultivo de *Pleurotus ostreatus* como fuente de nutrientes para las plantas.
        - **Control natural de hongos** — compuestos naturales, como el propóleo rojo, y nanomateriales contra hongos que atacan el maíz y hongos de importancia clínica.
        - **Bioinsumos microbianos** — bacterias como *Azospirillum* y *Bacillus* al servicio del crecimiento de las plantas.
        - **Abejas sin aguijón** — caracterización de la miel de jataí (*Tetragonisca angustula*).

        [Conozca los proyectos →](investigacion/)
    design:
      columns: '1'

  - block: collection
    id: destaques
    content:
      title: Publicaciones destacadas
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
      title: Publicaciones recientes
      text: ''
      count: 5
      filters:
        folders:
          - publications
        exclude_featured: false
      archive:
        enable: true
        text: Ver todas las publicaciones
        link: publicaciones/
    design:
      view: citation

  - block: collection
    id: noticias
    content:
      title: Noticias
      count: 3
      filters:
        folders:
          - blog
      archive:
        enable: true
        text: Ver todas las noticias
        link: noticias/
    design:
      view: card
      show_read_time: false
---
