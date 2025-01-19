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
      subtitle: LLMs can be Fooled into Labelling a Document as Relevant
      text: |

        {{% chenglongma_countdown date="2025-02-14 12:00" %}}
        
        **Speaker:** [Marwah Alaofi](https://marwahalaofi.com/)
        
        **Date:** 14th February 2025
        
        **Time:** 12:00 PM
        
        **Location:** RMIT University & Online
        
        **Abstract:**

        Large Language Models ( LLM s) are increasingly being used to assess the relevance of information objects. 
        This work reports on experiments to study the labelling of short texts (i.e., passages) for relevance, using 
        multiple open-source and proprietary LLMs. While the overall agreement of some LLM s with human judgements is
        comparable to human-to-human agreement measured in previous research, LLM s are more likely to label passages
        as relevant compared to human judges, indicating that LLM labels denoting non-relevance are more reliable than
        those indicating relevance.
        
        {{% cta cta_link="./talks/" cta_text="Register Now →" cta_new_tab="true" %}}

    design:
      columns: '1'
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
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen text-white
  - block: hero
    content:
      title: |
        TIGER Talks
      image:
        filename: welcome.jpeg
      text: |
        <br>

        "Chuffing~" 👋

        Empowering academic collaboration and innovation through inclusive and interdisciplinary discussions in IR, 
        RecSys, NLP, HCI, LLM and beyond.
        
        Andrew Turpin founded TIGER in 2006 and organized weekly meetings for quite some time. TIGER aims to foster a 
        vibrant research community by connecting students, staff, and external collaborators to explore cutting-edge 
        topics, share insights, and advance knowledge across diverse domains.
  
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
