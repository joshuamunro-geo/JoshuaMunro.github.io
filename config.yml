# Site settings
title: Joshua Munro
email: joshua.munro@utexas.edu
description: Personal webpage of Joshua Munro
baseurl: ""
url: ""

# Google analytics ID: Uncomment and your own, if you like
# google_analytics: XX
# google_analytics_4: XXX
# google_tag_manager: XXX

# Footer info
affiliation: >
   Joshua Munro<br/>
    Ph.D. Geochemistry Student<br/>
    The University of Texas at Austin

location: >
  Department of Earth and Planetary Sciences
  Jackson School of Geosciences
  University of Texas at Austin
  Austin, TX 78712

contact: >
    <a href="mailto:joshua.munro@utexas.edu" target="_blank"><i class="fa fa-envelope fa-1x"></i> Contact Meg via email</a> <br/>
   

# Pages shown in navbar
nav_pages:
  - name: about
  - name: publications
  - name: random

include:
  - .htaccess
  - _pages
  - _posts

# Conversion
markdown: kramdown
highlighter: rouge
lsi: false
excerpt_separator: "\n\n"
incremental: false

# Markdown Processing
kramdown:
  input: GFM
  hard_wrap: false
  auto_ids: true
  footnote_nr: 1
  entity_output: as_char
  toc_levels: 1..6
  smart_quotes: lsquo,rsquo,ldquo,rdquo
  enable_coderay: false
  parse_block_html: true # default for kramdown is false. This will enable using Markdown links


plugins: ['jekyll/scholar']

google_analytics: G-Y0S0FH2BHK

scholar:

  last_name: Doe
  first_name: [John]

  style: citesty
  locale: en

  source: /assets/
  bibliography: ref.bib
  bibliography_template: bibtemplate
  sort_by: year, month
  order: descending

  replace_strings: true
  join_strings: true

  details_dir: bibliography
  details_layout: bibtex.html
  details_link: Details

  query: "@*"

  bibliography_list_attributes:
    reversed: "reversed"

exclude:
  - Gemfile
  - Gemfile.lock
  - update_boostrap.sh
  - switch_theme.sh
  - tags
  - Rakefile
  - vendor
