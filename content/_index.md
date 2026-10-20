---
title: ''
date: 2026-10-15
type: landing
sections:
  - block: hero
    content:
      announcement:
        badge:
          text: Novidade
          color: green
        text: Três trabalhos no IUMS 2026, em Lisboa.
        link:
          text: Saiba mais
          url: noticias/2026-10-iums-2026-lisboa/
      eyebrow: Divulgação científica · FEIS-UNESP
      title: Fungos, solo e [ciência que chega à sociedade]
      text: Pesquisa em micologia, microbiologia do solo e bioinsumos, contada de um jeito simples, para quem planta, estuda ou só tem curiosidade.
      primary_action:
        text: Conheça a pesquisa
        url: pesquisa/
        icon: arrow-right
      secondary_action:
        text: Quem sou eu
        url: sobre/
    design:
      background:
        gradient_mesh:
          enable: true
      size: compact
  - block: features
    content:
      title: O que eu pesquiso
      text: Quatro frentes, um objetivo comum, uma agricultura que depende menos de químicos e aproveita melhor o que a natureza oferece.
      subtitle: Linhas de pesquisa
      items:
        - name: Economia circular com cogumelos
          description: O substrato que sobra do cultivo de *Pleurotus ostreatus* vira fonte de nutrientes para as plantas.
          icon: arrow-path
        - name: Controle natural de fungos
          description: Própolis vermelha e nanomateriais contra fungos que atacam o milho e fungos de importância clínica.
          icon: shield-check
        - name: Bioinsumos microbianos
          description: Bactérias como *Azospirillum* e *Bacillus* a serviço do crescimento das plantas.
          icon: beaker
        - name: Abelhas sem ferrão
          description: Caracterização do mel de jataí (*Tetragonisca angustula*).
          icon: bug-ant
    design:
      layout: grid
    id: linhas
  - block: collection
    content:
      title: Últimas notícias
      count: 3
      archive:
        text: Ver todas as notícias
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
      title: Publicações em destaque
      archive:
        text: Ver todas as publicações
        enable: true
        link: publicacoes/
      filters:
        featured_only: true
        folders:
          - publications
    design:
      view: citation
    id: destaques
  - block: cta-card
    content:
      title: Ciência no seu feed
      text: Bastidores do laboratório, curiosidades sobre fungos e novidades da pesquisa, também no Instagram.
      button:
        text: Acompanhe
        url: https://linktr.ee/gfspesquisa
        icon: arrow-right
    design:
      card:
        text_color: light
summary: ''
---
