---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        THE YOON GROUP
      image:
        filename: biopdb_13.png #welcome.jpg
        position: center
        size: cover
        filters:
            brightness: 1
##          parallax: false
##          position: center
##          size: cover
##          text_color_light: true
##      spacing:
##        padding: ['20px', '0', '20px', '0']
##      css_class: fullscreen
      text: |
        <br>
        
        THE YOON GROUP will be a center of excellence for Multiscale Computational Modeling and Artificial Intelligence research, teaching, and practice towards Materials Science and Engineering since its founding in 2025.
  
#  - block: collection
#    content:
#      title: Latest News
#      subtitle:
#      text:
#      count: 5
#      filters:
#        author: ''
#        category: ''
#        exclude_featured: false
#        publication_type: ''
#        tag: ''
#      offset: 0
#      order: desc
#      page_type: post
#    design:
#      view: card
#      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: Baylor_university_campus.jpg #coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
