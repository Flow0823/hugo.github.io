---
# Leave the homepage title empty to use the site title
title: ELDERS Research Group
date: 2025-07-17
type: landing

sections:

  - block: hero
    content:
      title: |
        ELDERS
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        ELDERS focuses on the social psychological and behavioral determinants of healthy aging, the construction of community elderly health management models, and comparative research on global healthy aging and management models.


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
      title: Latest Articles
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'
    
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

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: features
    content:
      title: "Research Pillars"
      items:
        - icon: brain
          icon_pack: fas
          name: Cognitive Aging
          description: Social neuroscience approaches
          text: "Focusing on the intersection of deep learning, artificial intelligence, and neuroscience, we build multimodal biological foundation models, promote innovative AI applications in life sciences, medicine, and brain science, and explore brain-inspired mechanisms of intelligent systems."

        - icon: heartbeat
          icon_pack: fas
          name: Behavioral Interventions
          description: RCTs for lifestyle modification
          text: "Focusing on the intersection of deep learning, artificial intelligence, and neuroscience, we build multimodal biological foundation models, promote innovative AI applications in life sciences, medicine, and brain science, and explore brain-inspired mechanisms of intelligent systems."

        - icon: users
          icon_pack: fas
          name: Social Connectivity
          description: Community-based participatory research
          text: "Focusing on the intersection of deep learning, artificial intelligence, and neuroscience, we build multimodal biological foundation models, promote innovative AI applications in life sciences, medicine, and brain science, and explore brain-inspired mechanisms of intelligent systems."
    
    design:
      columns: '3'

---
