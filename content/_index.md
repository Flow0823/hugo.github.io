---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Team philosophy
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        ELDERS Empowering Later-life inDependence via Education, Research & Support.

    
  - block: hero
    content:
      title: |
        Elders
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        ELDERS focuses on the social psychological and behavioral determinants of healthy aging, the construction of community elderly health management models, and comparative research on global healthy aging and management models.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  # 
  # - block: markdown
  #  content:
  #    title:
  #    subtitle: ''
  #    text:
  #  design:
  #    columns: '1'
  #    background:
  #      image: 
  #        filename: coders.jpg
  #        filters:
  #          brightness: 1
  #        parallax: false
  #        position: center
  #        size: cover
  #        text_color_light: true
  #    spacing:
  #      padding: ['20px', '0', '20px', '0']
  #    css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
