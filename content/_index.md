---
# Leave the homepage title empty to use the site title
title:
date: 2025-01-01
type: landing

sections:
  - block: markdown
    content:
      title: Upcoming Talks
      subtitle: Here are the next three talks scheduled at TIGER Talks.
      text: |

        {{% chenglongma_countdown date="2025-01-14 12:00" %}}
        
        {{% cta cta_link="./talks/" cta_text="View all talks →" %}}
    design:
      columns: '1'
      background:
        image:
          filename: upcoming-talks.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  - block: hero
    content:
      title: |
        TIGER Talks
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Welcome to the TIGER Talks website. Here you will find information about our upcoming events, latest news, and preprints.
        
  
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
      title: Upcoming Talks
      subtitle: Here are the next three talks scheduled at TIGER Talks.
      text: |
        asdfsadf
        sadf
        www
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

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
