---
# Página de inicio (español). Las secciones aparecen en el orden de abajo.
# La presentación personal (foto, bio y formación) está en la página "Sobre mí".
title: ''
summary: ''
date: 2026-10-15
type: landing

sections:
  - block: hero
    content:
      announcement:
        badge:
          text: Novedad
          color: green
        text: Presentaré dos trabajos en el IUMS 2026, en Lisboa.
        link:
          text: Más información
          url: noticias/2026-10-iums-2026-lisboa/
      eyebrow: Divulgación científica · FEIS-UNESP
      title: Hongos, suelo y [ciencia que llega al campo]
      text: Investigación en micología, microbiología del suelo y bioinsumos, contada de forma sencilla para quien cultiva, estudia o simplemente tiene curiosidad.
      primary_action:
        text: Conoce la investigación
        url: investigacion/
        icon: arrow-right
      secondary_action:
        text: Quién soy
        url: sobre-mi/
    design:
      size: compact
      background:
        gradient_mesh:
          enable: true

  - block: features
    id: linhas
    content:
      subtitle: Líneas de investigación
      title: Qué investigo
      text: 'Cuatro frentes, un objetivo común: una agricultura que dependa menos de químicos y aproveche mejor lo que ofrece la naturaleza.'
      items:
        - name: Economía circular con hongos comestibles
          icon: arrow-path
          description: El sustrato que queda del cultivo de *Pleurotus ostreatus* se convierte en fuente de nutrientes para las plantas.
        - name: Control natural de hongos
          icon: shield-check
          description: Propóleo rojo y nanomateriales contra hongos que atacan el maíz y hongos de importancia clínica.
        - name: Bioinsumos microbianos
          icon: beaker
          description: Bacterias como *Azospirillum* y *Bacillus* al servicio del crecimiento de las plantas.
        - name: Abejas sin aguijón
          icon: bug-ant
          description: Caracterización de la miel de jataí (*Tetragonisca angustula*).

    design:
      layout: grid

  - block: collection
    id: noticias
    content:
      title: Últimas noticias
      count: 3
      filters:
        folders:
          - blog
      archive:
        enable: true
        text: Ver todas las noticias
        link: noticias/
    design:
      view: article-grid
      columns: 3
      show_read_time: false

  - block: collection
    id: destaques
    content:
      title: Publicaciones destacadas
      filters:
        folders:
          - publications
        featured_only: true
      archive:
        enable: true
        text: Ver todas las publicaciones
        link: publicaciones/
    design:
      view: citation

  - block: cta-card
    content:
      title: Ciencia en tu feed
      text: Detrás de escena del laboratorio, curiosidades sobre hongos y novedades de la investigación, también en Instagram.
      button:
        text: Sígueme
        url: https://linktr.ee/gfspesquisa
        icon: arrow-right
    design:
      card:
        text_color: light
---
