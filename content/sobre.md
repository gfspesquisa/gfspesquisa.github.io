---
title: 'Sobre'
date: 2026-10-15
type: landing
design:
  spacing: '5rem'
# Os dados desta página vêm do seu perfil (data/authors/me.yaml),
# editável pelo painel em "Equipe" → "Gabriel Felix da Silva".
sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Ver publicações
        url: /publicacoes/
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
  - block: resume-experience
    content:
      username: me
    design:
      date_format: '01/2006'
      is_education_first: true
  - block: resume-skills
    content:
      title: Competências
      username: me
---
