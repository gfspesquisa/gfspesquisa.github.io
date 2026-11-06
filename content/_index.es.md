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
        text: Lo más destacado del IUMS 2026, en Lisboa.
        link:
          text: Más información
          url: noticias/2026-11-iums-2026-destaques/
      eyebrow: Divulgación científica · FEIS-UNESP
      title: Hongos, suelo y [ciencia que llega a la sociedad]
      text: Investigación en micología, fitopatología y microbiología del suelo desde la perspectiva de Una Salud, contada de forma sencilla para quien cultiva, estudia o simplemente tiene curiosidad.
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
      text: 'Cuatro frentes y un mismo eje, Una Salud (One Health): la salud de las plantas, las personas y el ambiente está conectada.'
      subtitle: Líneas de investigación
      items:
        - name: Bioprospección de microorganismos
          description: Búsqueda de microorganismos con potencial para el control de fitopatógenos.
          icon: magnifying-glass
        - name: Biomateriales contra hongos fitopatógenos
          description: Propóleo rojo y compuestos con plata para el control de hongos como *Fusarium verticillioides*.
          icon: shield-check
        - name: Residuos de la fungicultura como bioinsumos
          description: El sustrato poscultivo de *Pleurotus ostreatus* como biofertilizante y acondicionador de sustrato.
          icon: arrow-path
        - name: Microorganismos benéficos en la producción vegetal
          description: Bacterias como *Bacillus* y hongos micorrícicos en el crecimiento de las plantas y la producción de plántulas.
          icon: beaker
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
