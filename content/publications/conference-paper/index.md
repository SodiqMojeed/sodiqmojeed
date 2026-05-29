---
title: 'Genetic Algorithm for Optimizing Group Assignments at Conferences'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Emma R. Zajdela

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-08-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['manuscript']

# Publication name and optional abbreviated publication name.
publication: In *HugoBlox Kit Conference*
publication_short: In *ICW*

abstract: Past research has emphasized the importance of team diversity for innovation. However, little is known about how to efficiently catalyze the assembling of novel interdisciplinary groups at conferences with multiple breakout sessions. This research aims to design conference interactions that maximize group diversity and minimize repeated meetings among attendees. We developed a genetic algorithm to assign conference participants to culturally and intellectually diverse groups, with fewer repeated meetings between pairs across multiple sessions. The algorithm begins by generating a random population. It then performs iterative pairwise swaps across all pairs of groups to maximize a global objective function that measures the population diversity. A pairwise swap between two groups improves their compositions if it does not decrease the sum of the groups’ diversity indexes; it does not increase the number of individuals with a pre-defined level of prior knowledge of other group members in each of the groups; and it does not increase the number of repeated meetings among group members. Simulation results show that the algorithm outperforms random group assignments in reducing the frequency of repeated meetings among conference participants, minimizing group prior knowledge, and maximizing group diversity with respect to participants’ gender, discipline, and country of residence. This algorithmic approach provides a unique mechanism for optimizing group assignments at conferences and summer schools to foster novel, interdisciplinary, and diverse collaborations. We validate the algorithm with interaction data from >120 students at two Santa Fe Institute Complexity Global Schools. We recommend using the algorithm at conferences and summer school to catalyze collaboration and innovation.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Team Assembling
  - Diversity
  - Innovation
  - Interdisciplinary Collaboration
  - Genetic Algorithm
  

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.5555/123456

# Custom links
links:
  #- type: pdf
  #  url: ""
  #- type: code
  #  url: https://github.com/HugoBlox/kit
  #- type: dataset
  # url: https://github.com/HugoBlox/kit
  #- type: slides
  #  url: https://www.slideshare.net/
  #- type: source
  #  url: https://github.com/HugoBlox/kit
  #- type: video
  #  url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'A collaboration network that emerged after a series of algorithmic group interactions. Nodes represent the countries of residence of collaborators. Edge weight illustrates the number of unique international collaborations among pairs.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
