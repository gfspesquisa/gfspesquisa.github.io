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
        text: Destaques do IUMS 2026, em Lisboa.
        link:
          text: Saiba mais
          url: noticias/2026-11-iums-2026-destaques/
      eyebrow: Divulgação científica · FEIS-UNESP
      title: Fungos, solo e [ciência que chega à sociedade]
      text: Pesquisa em micologia, fitopatologia e microbiologia do solo, sob a perspectiva da Saúde Única, contada de um jeito simples para quem planta, estuda ou só tem curiosidade.
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
      text: 'Quatro frentes e um mesmo eixo, a Saúde Única (One Health): a saúde das plantas, das pessoas e do ambiente está conectada.'
      subtitle: Linhas de pesquisa
      items:
        - name: Bioprospecção de microrganismos
          description: Busca de microrganismos com potencial para o controle de fitopatógenos.
          icon: magnifying-glass
        - name: Biomateriais contra fungos fitopatogênicos
          description: Própolis vermelha e compósitos com prata no controle de fungos como *Fusarium verticillioides*.
          icon: shield-check
        - name: Resíduos da fungicultura como bioinsumos
          description: O substrato pós-cultivo de *Pleurotus ostreatus* como biofertilizante e condicionador de substrato.
          icon: arrow-path
        - name: Microrganismos benéficos na produção vegetal
          description: Bactérias como *Bacillus* e fungos micorrízicos no crescimento das plantas e na produção de mudas.
          icon: beaker
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
