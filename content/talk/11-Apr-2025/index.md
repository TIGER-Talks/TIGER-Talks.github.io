---
title: LLMs can be Fooled into Labelling a Document as Relevant
draft: false

event: "TIGER Talk: LLMs can be Fooled into Labelling a Document as Relevant"
# event_url: https://example.org

location: "**B080.09.012** at RMIT & MS Teams"
address:
  street: Building 80/435-457 Swanston St
  city: Melbourne
  region: VIC
  postcode: '3000'
  country: Australia

speaker: '{{% mention "Marwah Alaofi" %}}'
#speaker_url: "https://marwahalaofi.com/"
summary: Marwah Alaofi presents her paper on how Large Language Models can be fooled into labelling a document as relevant. The paper won the **Best Paper Honorable Mention** award at SIGIR-AP'24.
abstract: 'This talk presents experiments to study the labelling of short texts (i.e., passages) for relevance, using multiple open-source and proprietary LLMs. While the overall agreement of some LLMs with human judgements is comparable to human-to-human agreement measured in previous research, LLMs are more likely to label passages as relevant compared to human judges, indicating that LLM labels denoting non-relevance are more reliable than those indicating relevance.
<br><br>
This observation prompts us to further examine cases where human judges and LLMs disagree, particularly when the human judge labels the passage as non-relevant and the LLM labels it as relevant. Results show a tendency for many LLMs to label passages that include the original query terms as relevant. We, therefore, conduct experiments to inject query words into random and irrelevant passages. The results demonstrate that LLMs are highly influenced by the presence of query words in the passages under assessment, even if the wider passage has no relevance to the query. This tendency of LLMs to be fooled by the mere presence of query words demonstrates a weakness in our current measures of LLM labelling: relying on overall agreement misses important patterns of failures. There is a real risk of bias in LLM-generated relevance labels and, therefore, a risk of bias in rankers trained on those labels.
<br><br>
Additionally, we investigate the effects of deliberately manipulating LLMs by instructing them to label passages as relevant. We find that such manipulation influences the performance of some LLMs, highlighting the critical need to consider potential vulnerabilities when deploying LLMs in real-world applications.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.

date: '2025-04-11T15:30:00+11:00'
date_end: '2025-04-11T16:30:00+11:00'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-04-04T09:00:00+11:00'

authors:
  - Marwah Alaofi
  - admin
author_notes:
  - "Speaker"
  - "Organiser"
tags: [Talk, IR, LLM, SIGIR-AP, Relevance, Labelling]

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Photo by [Victor Serban](https://unsplash.com/@victorserban?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash") on [Unsplash](https://unsplash.com/photos/woman-in-blue-and-white-dress-SgAqgz9tEKw?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash")'
  focal_point: Right

url_code: ''
url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3673791.3698431'
url_slides: '/uploads/slides/11-Apr-2025.pdf'
url_video: 'https://rmiteduau-my.sharepoint.com/:v:/g/personal/chenglong_ma_rmit_edu_au/ETe_uNdnSWBPlxIEmEdD1_MB0DkuoWUHPWCjTHWsXWlFcQ?e=TyYbDD&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D'

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

<!-- {{% cta cta_link="https://events.teams.microsoft.com/event/9f405cc9-49a6-45b6-bf61-5d9fb7f8eb44@d1323671-cdbe-4417-b4d4-bdb24b51316b" cta_text="Register Now →" cta_new_tab="true" %}} -->

<!-- {{% callout warning %}} -->
<!-- The date and time for this talk is to be announced soon. -->
<!-- {{% /callout %}} -->

> [!SUCCESS] Congratulations! 🎉
> 🏆 The paper won the **Best Paper Honorable Mention** award at SIGIR-AP'24.
> 
> ![Marwah is showing the Best Paper Honorable Mention award at SIGIR-AP'24](/uploads/talks/11-Apr-2025/award.jpg "The paper won the Best Paper Honorable Mention award at SIGIR-AP'24.<br>Source: [
Prof. Mark Sanderson's LinkedIn Post.](https://www.linkedin.com/posts/marksandersonresearcher_many-congratulations-to-marwah-alaofi-on-activity-7273106582949785601-6fJz/)")

<!-- > [!MEMO] -->
<!-- > The **shared resources** will be available after the talk. Stay tuned! -->
<!-- > -->

### Talk Recording (RMIT Account Required)

<iframe src="https://rmiteduau-my.sharepoint.com/personal/chenglong_ma_rmit_edu_au/_layouts/15/embed.aspx?UniqueId=1e2a84b8-e8eb-4981-b424-ef1bd82da099&embed=%7B%22ust%22%3Atrue%2C%22hv%22%3A%22CopyEmbedCode%22%7D&referrer=StreamWebApp&referrerScenario=EmbedDialog.Create" width="800" height="450" frameborder="0" scrolling="no" allowfullscreen title="[TIGER Talk] _A Weighted Correlation Index for Rankings with Ties_, by Prof. Sebastiano Vigna [080.09.012 & MS Teams]-20250509_154339-Meeting Recording.mp4"></iframe>

### Getting There

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3152.222093623283!2d144.96027981258027!3d-37.80826657186005!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad642cb67178b05%3A0xe5c2160ff784f314!2sBuilding%2080%20(Swanston%20Academic%20Building)%20-%20RMIT%20University!5e0!3m2!1sen!2sau!4v1738711638555!5m2!1sen!2sau" width="800" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
