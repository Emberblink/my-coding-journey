---
title: "Home"
layout: "home"

hero:
  title: "Welcome to My Coding Journey 👋"
  description: |
    Hi there! I'm a self-taught developer currently learning **Python**, **GDScript**, and building small games in **Godot**.  
    This site is where I document my journey, share my projects, and reflect on what I learn along the way.

    > "A journey of a thousand miles begins with a single step." — Lao Tzu

    Thanks for stopping by — I hope you enjoy watching this adventure unfold!
  actions:
    - label: "View Portfolio"
      url: "/portfolio/"
      primary: true
    - label: "Read Blog"
      url: "/blog/"

sections:
  - title: "Latest Blog Posts"
    linkTitle: "View all posts"
    linkUrl: "/blog/"
    list:
      limit: 3
      section: "blog"

  - title: "Featured Projects"
    linkTitle: "View all projects"
    linkUrl: "/portfolio/"
    list:
      limit: 3
      section: "portfolio"
      nested: true
---
