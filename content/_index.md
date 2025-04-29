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
      subtitle: A Weighted Correlation Index for Rankings with Ties
      text: |

        {{% chenglongma_countdown date="2025-05-09 15:30" %}}
        
        **Speaker:** {{% mention "Sebastiano Vigna" %}}
        
        **Date:** 09 May, 2025
        
        **Time:** 3:30 PM - 4:30 PM (AEDT)
        
        **Location:** **B080.09.012** at RMIT University & MS Teams
        
        **Abstract:**
        Understanding the correlation between two different scores for the same set of items is a common problem in graph analysis and information retrieval. The most commonly used statistics that quantifies this correlation is Kendall's $\tau$; however, the standard definition fails to capture that discordances between items with high rank are more important than those between items with low rank. Recently, a new measure of correlation based on average precision has been proposed to solve this problem, but like many alternative proposals in the literature it assumes that there are no ties in the scores. This is a major deficiency in a number of contexts, and in particular when comparing centrality scores on large graphs, as the obvious baseline, indegree, has a very large number of ties in social networks and web graphs. We propose to extend Kendall's definition in a natural way to take into account weights in the presence of ties. We prove a number of interesting mathematical properties of our generalization and describe an O(n log n) algorithm for its computation. We also validate the usefulness of our weighted measure of correlation using experimental data on social networks and web graphs.

        {{% cta cta_link="./talk/09-may-2025/" cta_text="Read More →" cta_new_tab="false" %}}

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
