---
# Página inicial. As seções aparecem na ordem abaixo.
# A apresentação pessoal (foto, bio e formação) fica na página "Sobre".
title: ''
summary: ''
date: 2026-10-15
type: landing

sections:
  - block: hero
    content:
      announcement:
        badge:
          text: Novidade
          color: green
        text: Vou apresentar dois trabalhos no IUMS 2026, em Lisboa.
        link:
          text: Saiba mais
          url: noticias/2026-10-iums-2026-lisboa/
      eyebrow: Divulgação científica · FEIS-UNESP
      title: Fungos, solo e [ciência que chega ao campo]
      text: Pesquisa em micologia, microbiologia do solo e bioinsumos, contada de um jeito simples, para quem planta, estuda ou só tem curiosidade.
      primary_action:
        text: Conheça a pesquisa
        url: pesquisa/
        icon: arrow-right
      secondary_action:
        text: Quem sou eu
        url: sobre/
    design:
      size: compact
      background:
        gradient_mesh:
          enable: true

  - block: features
    id: linhas
    content:
      subtitle: Linhas de pesquisa
      title: O que eu pesquiso
      text: Quatro frentes, um objetivo comum, uma agricultura que depende menos de químicos e aproveita melhor o que a natureza oferece.
      items:
        - name: Economia circular com cogumelos
          icon: arrow-path
          description: O substrato que sobra do cultivo de *Pleurotus ostreatus* vira fonte de nutrientes para as plantas.
        - name: Controle natural de fungos
          icon: shield-check
          description: Própolis vermelha e nanomateriais contra fungos que atacam o milho e fungos de importância clínica.
        - name: Bioinsumos microbianos
          icon: beaker
          description: Bactérias como *Azospirillum* e *Bacillus* a serviço do crescimento das plantas.
        - name: Abelhas sem ferrão
          icon: bug-ant
          description: Caracterização do mel de jataí (*Tetragonisca angustula*).

    design:
      layout: grid

  - block: collection
    id: noticias
    content:
      title: Últimas notícias
      count: 3
      filters:
        folders:
          - blog
      archive:
        enable: true
        text: Ver todas as notícias
        link: noticias/
    design:
      view: article-grid
      columns: 3
      show_read_time: false

  - block: collection
    id: destaques
    content:
      title: Publicações em destaque
      filters:
        folders:
          - publications
        featured_only: true
      archive:
        enable: true
        text: Ver todas as publicações
        link: publicacoes/
    design:
      view: citation

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
---
