---
title: A Weighted Correlation Index for Rankings with Ties
draft: false

event: "TIGER Talk: A Weighted Correlation Index for Rankings with Ties"
# event_url: https://example.org

location: "**B080.09.012** at RMIT & MS Teams"
address:
  street: Building 80/435-457 Swanston St
  city: Melbourne
  region: VIC
  postcode: '3000'
  country: Australia

speaker: '{{% mention "Sebastiano Vigna" %}}'
#speaker_url: "https://marwahalaofi.com/"
summary: Sebastiano Vigna presents a groundbreaking weighted generalization of Kendall's $\tau$ that brilliantly handles tied ranks, powered by an $O(nlogn)$ algorithm and validated on massive social and web graphs.
abstract: "Understanding the correlation between two different scores for the same set of items is a common problem in 
graph analysis and information retrieval. The most commonly used
statistics that quantifies this correlation is Kendall's $\tau$; 
however, the standard definition fails to capture that discordances 
between items with high rank are more important than those between 
items with low rank. Recently, a new measure of correlation based on 
average precision has been proposed to solve this problem, but like 
many alternative proposals in the literature it assumes that there 
are no ties in the scores. This is a major deficiency in a number 
of contexts, and in particular when comparing centrality scores on
large graphs, as the obvious baseline, indegree, has a very large 
number of ties in social networks and web graphs. We propose to 
extend Kendall's definition in a natural way to take into account weights in the
presence of ties. We prove a number of interesting mathematical properties of
our generalization and describe an $O(n log n)$ algorithm for its computation. 
We also validate the usefulness of our weighted measure of correlation using 
experimental data on social networks and web graphs."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.

date: '2025-05-09T15:30:00+11:00'
date_end: '2025-05-09T16:30:00+11:00'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-04-29T09:00:00+11:00'

authors:
  - Sebastiano Vigna
  - admin
author_notes:
  - "Speaker"
  - "Organiser"
tags: [Talk, IR, Large graph analysis, Correlation metrics, Centrality measures]

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Photo by <a href="https://unsplash.com/@guerrillabuzz?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">GuerrillaBuzz</a> on <a href="https://unsplash.com/photos/diagram-7hA2wqBcSF8?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>'
  focal_point: Right

url_code: ''
url_pdf: 'https://vigna.di.unimi.it/ftp/papers/WeightedTau.pdf'
url_slides: '/uploads/slides/09-May-2025.pdf'
url_video: 'https://rmiteduau-my.sharepoint.com/:v:/g/personal/chenglong_ma_rmit_edu_au/EbiEKh7r6IFJtCTvG9gtoJkBciot7eioYNMZDKS6gHpi3A?e=qIZbZO&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

### Recording of the Talk (RMIT Account Required)

<iframe src="https://rmiteduau-my.sharepoint.com/personal/chenglong_ma_rmit_edu_au/_layouts/15/embed.aspx?UniqueId=1e2a84b8-e8eb-4981-b424-ef1bd82da099&embed=%7B%22ust%22%3Atrue%2C%22hv%22%3A%22CopyEmbedCode%22%7D&referrer=StreamWebApp&referrerScenario=EmbedDialog.Create" width="800" height="450" frameborder="0" scrolling="no" allowfullscreen title="[TIGER Talk] _A Weighted Correlation Index for Rankings with Ties_, by Prof. Sebastiano Vigna [080.09.012 & MS Teams]-20250509_154339-Meeting Recording.mp4"></iframe>

### Getting There

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3152.222093623283!2d144.96027981258027!3d-37.80826657186005!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad642cb67178b05%3A0xe5c2160ff784f314!2sBuilding%2080%20(Swanston%20Academic%20Building)%20-%20RMIT%20University!5e0!3m2!1sen!2sau!4v1738711638555!5m2!1sen!2sau" width="800" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
