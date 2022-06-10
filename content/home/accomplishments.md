---
# An instance of the Accomplishments widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: accomplishments

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

# Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
title: 'Additional education and certifications'
subtitle:

# Date format
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
item:
  - certificate_url: https://coursera.org/share/d77edd109cedb94424aff8e0a96d9bee
    date_end: '2022-03-17'
    date_start: '2022-01-25'
    description: '30-hour specialisation introducing the AWS ecosystem and walking through hands-on exercises about DevOps concepts and tasks.'
    organization: Coursera
    organization_url: https://www.coursera.org
    title: DevOps on AWS
    url: ''
  - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/dc780825ade94239e7601d24de6e22a564805470
    date_end: '2018-07-12'
    date_start: '2018-06-12'
    description: '4-hour course about fitting hierarchical models with random effects in R using the `lmer` package.'
    organization: DataCamp
    organization_url: https://www.datacamp.com/
    title: Hierarchical and Mixed Effects Models in R
    url: ''

design:
  background:
    # Name of image in `assets/media/`.
    image: background2.jpg
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.2
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true
  columns: '2'
---
