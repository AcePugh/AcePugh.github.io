---
# Leave the homepage title empty to use the site title
#page title
title: ""
date: 2022-10-24
#Page type - we want a landing page (such as a homepage)
type: landing

design:
  # Default section spacing
  spacing: "6rem"

# Landing page sections - add as many different content blocks as you like
sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I'm a postdoctoral research scientist at the USDA-ARS. My mission is to use remote sensing and artificial intelligence tools to augment the breeding and production of key crop species.

        I use a wide range of remote sensing tools such as small unoccupied aircraft systems (sUAS), or "drones", satellite imagery, and field-based proximal sensors. Once these data are collected, I use machine learning techniques to estimate or predict key traits including yield, drought tolerance, quality, and more.
        
        Please contact me if you'd like to ask about my work or if you're interested in collaborating!

        Disclaimer: The views expressed on this website are my own and do not necessarily reflect the views of the USDA or the U.S. Government.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: article-grid
#      columns: 1
  - block: collection
    id: blog
    content:
      title: Recent Blog Posts
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
