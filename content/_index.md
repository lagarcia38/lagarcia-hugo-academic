---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor
          company: University of Utah Kahlert School of Computing
          company_url: 'https://cs.utah.edu'
          company_logo: org-gc
          location: Salt Lake City, Utah
          date_start: '2023-07-01'
          date_end: ''
        - title: Research Lead and Research Assistant Professor
          company: University of Southern California, Information Sciences Institute
          company_url: 'https://isi.edu'
          company_logo: org-x
          location: California
          date_start: '2020-07-01'
          date_end: '2023-06-30'
    design:
      columns: '2'
---
