---
# Display name
title: Sebastiano Vigna

# Full Name (for SEO)
first_name: Sebastiano
last_name: Vigna

# Is this the primary user of the site?
superuser: false

# Role/position
role: Professor at the Università degli Studi di Milano

# Organizations/Affiliations
organizations:
  - name: Università degli Studi di Milano
    url: 'https://www.unimi.it/'

# Short bio (displayed in user profile at end of posts)
bio: Sebastiano Vigna's research focuses on the interaction between theory and practice.
  He has worked on theoretical topics such as computability on the reals, distributed computability, self-stabilization,
  minimal perfect hashing, succinct data structures, query recommendation, algorithms for large graphs,
  pseudorandom number generation, theoretical/experimental analysis of spectral rankings such as PageRank,
  and axiomatization of centrality measures.

interests:
  - Compression of web and social graphs
  - Analysis of web and social graphs
  - Pseudorandom number generators
  - Efficient data structures for large datasets

#education:
#  courses:
#    - course: PhD in Computer Science
#      institution: RMIT University
#      year: 2020
#    - course: Master in Information Technology
#      institution: RMIT University
#      year: 2018

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: globe
    icon_pack: fas
    link: https://vigna.di.unimi.it/
#  - icon: dblp
#    icon_pack: ai
#    link: https://dblp.org/pid/71/5174.html
  - icon: google-scholar
    icon_pack: ai
    link: https://scholar.google.com/citations?user=WL8DH4YAAAAJ&hl=en
#  - icon: linkedin
#    icon_pack: fab
#    link: https://www.linkedin.com/in/enrique-amig%C3%B3-8357711a/
  - icon: orcid
    icon_pack: ai
    link: https://orcid.org/0000-0002-3257-651X
  - icon: github
    icon_pack: fab
    link: https://github.com/vigna
#  - icon: x-twitter
#    icon_pack: fab
#    link: https://twitter.com/marwah_k
#  - icon: instagram
#    icon_pack: fab
#    link: https://www.instagram.com/enrique_amigo/
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: 'sebastiano.vigna@gmail.com'
#email: 'enrique@lsi.uned.es'

# Highlight the author in author lists? (true/false)
highlight_name: true

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
  - Speakers
---

Sebastiano Vigna's research focuses on the interaction between theory and practice. 
He has worked on theoretical topics such as computability on the reals, distributed computability, self-stabilization, 
minimal perfect hashing, succinct data structures, query recommendation, algorithms for large graphs, 
pseudorandom number generation, theoretical/experimental analysis of spectral rankings such as PageRank, 
and axiomatization of centrality measures. 
However, he is also (co)author of several widely used software tools ranging from high-performance Java libraries to 
Scipy, a search engine, a crawler, a text editor, and a graph compression framework that is used by Common Crawl and 
Software Heritage for managing huge graphs. 
He recently ported the latter to Rust, supported by a new Rust framework for zero-copy deserialization and memory mapping. 
In 2011 he collaborated to the first computation of the distance distribution of the whole Facebook graph, from which 
it was possible to evince that on Facebook there are just 3.74 degrees of separation. 
His work on the Elias-Fano encoding and quasi-succinct indices has been implemented in [Facebook's "folly" library](https://github.com/facebook/folly/blob/main/folly/compression/elias_fano/EliasFanoCoding.h). 
He also proposed the first open ranking of Wikipedia pages (http://wikirank.di.unimi.it/), 
which is based on his body of work on centrality in networks. 
His pseudorandom number generator xorshift128+ is the current stock generator of Google's V8 JavaScript engine, 
and it is used by Chrome, Safari, Firefox, Edge, and Node.js; it is also the stock generator of the Erlang language, 
whereas his generator xoshiro256++ is the SmallRng of Rust, and xoshiro256** is the stock generator of the .NET framework and Lua; 
he also participated with Guy Steele to the redesign of the Java 18 random API, which now includes several of his generators.
