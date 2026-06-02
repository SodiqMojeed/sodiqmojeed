---
title: 'Experience'
date: 2026-05-30
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: collection
    id: awards-gallery
    content:
      title: Honors & Awards
      subtitle: 'Recognition for academic and research excellence'
      # Filters the content to only show items from your new awards folder
      filters:
        folders:
          - awards
        tag: ''
        category: ''
        publication_type: ''
        exclude_featured: false
      # Sort by date (newest awards first)
      sort_by: 'Date'
      sort_ascending: false
      count: 10
    design:
      # 'article-grid' or 'card' shows the featured images you added
      view: article-grid
      columns: '2'
      spacing:
        padding: [0, 0, 0, 0]


  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: me
  #- block: resume-awards
  #  content:
  #    title: Awards
  #    username: me
  #- block: resume-languages
  #  content:
  #    title: Languages
  #    username: me
---
