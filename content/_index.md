---
# Leave the homepage title empty to use the site title
title:
date: 2025-01-01
type: landing

sections:
  - block: markdown
    id: section-upcoming-talks
    content:
      title: Upcoming TIGER Talk
      subtitle: "From PhD to Industry: LLMs and Career Paths"
      text: |

        {{% chenglongma_countdown date="2025-06-11 14:30" %}}
        
        **Speaker:** {{% mention "Amin Sadri" %}}
        
        **Date:** 11 June, 2025
        
        **Time:** 2:30 PM - 3:30 PM (AEDT)
        
        **Location:** **B080.11.009** at RMIT University & MS Teams
        
        **Abstract:**
        This talk is divided into two parts. In the first, we'll explore the latest advances in artificial intelligence, from large language models (LLMs) to cutting-edge applications across industries. We'll also touch on the intriguing question of whether AI could ever approach a state of "infinite intelligence", and what that might mean for both research and society. In the second part, I'll share my personal journey transitioning from a PhD in machine learning to a role as Principal Data Scientist. We'll discuss the key differences between academic and industry ML, real-world case studies, and offer actionable career advice for PhD students interested in moving to industry—covering skills to build, common pitfalls, and how to bridge the gap between research and practical impact.

        {{% cta cta_link="./talk/11-jun-2025/" cta_text="Read More →" cta_new_tab="false" %}}

    design:
      columns: '1'
#      https://docs.hugoblox.com/getting-started/page-builder/#background
      background:
#        gradient_start: '#4bb4e3'
#        gradient_end: '#2b94c3'
#        # The gradient angle from 0-360 degrees
#        gradient_angle: 180
        
        image:
          filename: upcoming-talks.jpg
          filters:
            brightness: 0.5
          parallax: false
          position: center
          size: cover
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen text-white
  - block: hero
    id: section-welcome
    content:
      title: TIGER Talks
      image:
        filename: welcome.jpeg
      text: |
        
        <br>
        
        **Chuffing~** 👋 We are a group of researchers and students who are passionate about Information Retrieval,
        Recommender Systems, Natural Language Processing, Human-Computer Interaction, Large Language Models, and beyond.

      cta:
        url: tour
        label: "Take a Tour"
        icon: "rocket"
        icon_pack: "fas"
#      cta_alt:
#        url: "https://example.com/learn-more"
#        label: "Learn More"
#      cta_note:
#        label: "No credit card required."
#    design:
#      css_style: 'font-size: 0.1em;'
#      background:
#        image: 
#          filename: welcome.jpeg
#          filters:
#            brightness: 1
#          parallax: false
#          position: top
#          size: cover
#      text_color_light: true
#      css_class: text-white      
#      spacing:
#        padding: ['20px', '0', '20px', '0']
  
  - block: collection
    content:
      title: Recent & Upcoming Talks
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
      page_type: talk
    design:
      view: card
      columns: '1'

#  - block: collection
#    content:
#      title: Latest Preprints
#      text: ""
#      count: 5
#      filters:
#        folders:
#          - publication
#        publication_type: 'article'
#    design:
#      view: citation
#      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image:
          filename: footer-banner.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
