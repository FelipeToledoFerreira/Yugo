---
# Leave the homepage title empty to use the site title
title: Felipe Ferreira
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
      
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
      
  - block: collection
    content:
      title: Recent Publications
      text: |-
    design:
      columns: '2'
      view: citation
      
  - block: contact
    id: contact
    content:
      title: Contact
      email: felipe3@ime.usp
      address:
        street: Rua do Matão 1010
        city: São Paulo
        region: SP
        postcode: 05508-090
        country: Brasil
        country_code: BR
        directions: Laboratory 250, Block A
---
