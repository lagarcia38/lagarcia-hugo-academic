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
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: group
    id: group-members
    content:
      title: Group Members
      subtitle: Meet the members of our research group
      members:
        - name: Jane Doe
          title: PhD Student
          bio: Jane is researching machine learning techniques.
          photo: images/jane-doe.jpg
          social:
            - icon: linkedin
              icon_pack: fab
              link: https://www.linkedin.com/in/jane-doe/
        - name: John Smith
          title: MSc Student
          bio: John is working on natural language processing.
          photo: images/john-smith.jpg
          social:
            - icon: twitter
              icon_pack: fab
              link: https://twitter.com/johnsmith
    design:
      view: team
      columns: '2'
---
