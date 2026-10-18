---
title: 'Sobre mí'
date: 2026-10-15
slug: sobre-mi
type: landing
design:
  spacing: '5rem'
# Los datos de esta página vienen de data/es/authors/me.yaml (español), sobre data/authors/me.yaml.
sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Ver publicaciones
        url: /es/publicaciones/
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
  - block: resume-experience
    content:
      username: me
    design:
      date_format: '01/2006'
      is_education_first: true
  - block: resume-skills
    content:
      title: Competencias
      username: me
---
