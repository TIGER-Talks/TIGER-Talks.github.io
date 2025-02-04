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
      subtitle: New Dimensions of Evaluation Amid the Rise of Large Language Models
      text: |

        {{% chenglongma_countdown date="2025-02-20 12:00" %}}
        
        **Speaker:** {{% mention "Enrique Amigo" %}}
        
        **Date:** 20 February, 2025
        
        **Time:** 12:00 PM - 1:00 PM (AEDT)
        
        **Location:** **B080.06.005** at RMIT University & MS Teams
        
        **Abstract:**
        So far, in information retrieval, recommendation systems, and artificial intelligence in general, automatic 
        offline evaluation benchmarks (based on comparisons between the output and a gold standard) have focused on **effectiveness**,
        alongside parallel research on some issues such as bias or diversity. However, with the emergence of large language models,
        it has become necessary to consider a broader spectrum of evaluation dimensions, including aspects such as **harmful content**,
        **explainability power**, **hallucination**, **informativeness** or **reasoning capabilities**. This talk presents a taxonomy of evaluation
        dimensions, as well as existing benchmarks and metrics, highlighting their strengths and limitations. The goal is to provide
        a comprehensive overview that enables the design of research work from different perspectives, as well as to outline a
        general methodology for offline evaluation of intelligent systems.

        {{% cta cta_link="./talk/20-feb-2025/" cta_text="Read More →" cta_new_tab="false" %}}
        {{% comment %}}
        {{% cta cta_link="./talks/" cta_text="Register Now →" cta_new_tab="true" %}}
        {{% /comment %}}

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
