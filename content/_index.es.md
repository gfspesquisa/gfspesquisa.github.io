---
title: ''
date: 2026-10-15
type: landing
sections:
  - block: hero
    content:
      announcement:
        badge:
          text: Novedad
          color: green
        text: Tres trabajos en el IUMS 2026, en Lisboa.
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
      background:
        gradient_mesh:
          enable: true
      size: compact
  - block: features
    content:
      title: Qué investigo
      text: 'Cuatro frentes, un objetivo común: una agricultura que dependa menos de químicos y aproveche mejor lo que ofrece la naturaleza.'
      subtitle: Líneas de investigación
      items:
        - name: Economía circular con hongos comestibles
          description: El sustrato que queda del cultivo de *Pleurotus ostreatus* se convierte en fuente de nutrientes para las plantas.
          icon: arrow-path
        - name: Control natural de hongos
          description: Propóleo rojo y nanomateriales contra hongos que atacan el maíz y hongos de importancia clínica.
          icon: shield-check
        - name: Bioinsumos microbianos
          description: Bacterias como *Azospirillum* y *Bacillus* al servicio del crecimiento de las plantas.
          icon: beaker
        - name: Abejas sin aguijón
          description: Caracterización de la miel de jataí (*Tetragonisca angustula*).
          icon: bug-ant
    design:
      layout: grid
    id: linhas
  - block: collection
    content:
      title: Últimas noticias
      count: 3
      archive:
        text: Ver todas las noticias
        enable: true
        link: noticias/
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
      title: Publicaciones destacadas
      archive:
        text: Ver todas las publicaciones
        enable: true
        link: publicaciones/
      filters:
        featured_only: true
        folders:
          - publications
    design:
      view: citation
    id: destaques
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
summary: ''
---
