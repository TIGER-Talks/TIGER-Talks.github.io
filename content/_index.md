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

        {{% chenglongma_countdown date="2025-04-11 15:30" %}}
        
        **Speaker:** {{% mention "Marwah Alaofi" %}}
        
        **Date:** 11 April, 2025
        
        **Time:** 3:30 PM - 4:30 PM (AEDT)
        
        **Location:** **B080.09.012** at RMIT University & MS Teams
        
        **Abstract:**
        This talk presents experiments to study the labelling of short texts (i.e., passages) for relevance, using multiple open-source and proprietary LLMs. While the overall agreement of some LLMs with human judgements is comparable to human-to-human agreement measured in previous research, LLMs are more likely to label passages as relevant compared to human judges, indicating that LLM labels denoting non-relevance are more reliable than those indicating relevance.

        This observation prompts us to further examine cases where human judges and LLMs disagree, particularly when the human judge labels the passage as non-relevant and the LLM labels it as relevant. Results show a tendency for many LLMs to label passages that include the original query terms as relevant. We, therefore, conduct experiments to inject query words into random and irrelevant passages. The results demonstrate that LLMs are highly influenced by the presence of query words in the passages under assessment, even if the wider passage has no relevance to the query. This tendency of LLMs to be fooled by the mere presence of query words demonstrates a weakness in our current measures of LLM labelling: relying on overall agreement misses important patterns of failures. There is a real risk of bias in LLM-generated relevance labels and, therefore, a risk of bias in rankers trained on those labels.

        Additionally, we investigate the effects of deliberately manipulating LLMs by instructing them to label passages as relevant. We find that such manipulation influences the performance of some LLMs, highlighting the critical need to consider potential vulnerabilities when deploying LLMs in real-world applications.

        {{% cta cta_link="./talk/11-apr-2025/" cta_text="Read More →" cta_new_tab="false" %}}

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
