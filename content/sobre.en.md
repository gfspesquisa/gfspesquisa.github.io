---
title: 'About'
date: 2026-10-15
slug: about
type: landing
design:
  spacing: '5rem'
# Data on this page comes from data/en/authors/me.yaml (English) on top of data/authors/me.yaml.
sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: See publications
        url: /en/publications/
      headings:
        about: 'About me'
        education: 'Education'
        interests: 'Interests'
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
      title: Skills
      username: me
---
