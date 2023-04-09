---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Work Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Data Scientist
    company: MACH (Fintech)
    company_url: 'hhttps://www.somosmach.com/'
    company_logo: mach
    location: Santiago, Chile
    date_start: '2022-08-30'
    #date_end: '2021-10-18'
    description: |2-
        * Used Apache Airflow to develop an analytical asset that triggered proactive retention initiatives when a significant drop in transaction frequency was detected.
        * Proposed and implemented an experimentation framework for A/B testing best practices.
        * Trained predictive machine learning models using AWS cloud infrastructure (SageMaker, Athena and Glue) and PySpark.
        * Evaluated the causal impact of referral campaigns using Matching when the use of randomised control groups was not feasible.

  - title: Data Scientist
    company: WOM (Telecommunications)
    company_url: 'https://novator.co.uk/portfolio/wom/'
    company_logo: logo-wom
    location: Santiago, Chile
    date_start: '2020-01-01'
    date_end: '2021-10-18'
    description: |2-
        * Used interpretable modeling techniques and unsupervised learning to guide the prioritisation of network infrastructure deployments. The resulting insights were made available to stakeholders via interactive reports, using packages such as flexdashboard and plotly.
        * Trained predictive models with the ML framework H2O to better target potential customers through call centre campaigns.
        * Performed impact evaluations of network investments using A/B testing, differences in differences, and matching.
        
  - title: Data Scientist
    company: Walmart Chile (Retail)
    company_url: 'https://corporate.walmart.com/about/chile'
    company_logo: Walmart_logo
    location: Santiago, Chile
    date_start: '2018-10-17'
    date_end: '2020-01-01'
    description: |2-
        * Developed data transformation processes and implemented machine learning models that allowed the deployment of a personalized marketing strategy for the company's most important local brand. This included the development of churn models and clustering on transactional data.
      * Led the development of an internal R package aimed at streamlining processes and accelerating deliveries in our area (find out more [here](https://cv.franciscoyira.com/project/walmart-chile-r-package/)).
      * Led the impact evaluation of the personalised marketing project by designing, implementing, and supervising A/B tests, in close collaboration with the CRM Ops team. This included devising solutions for increasing statistical power in contexts of small treatment effects.
      * Introduced the use of version control and unit tests to the team.
    
  - title: Data Analyst
    company: Walmart Chile (Retail)
    company_url: 'https://corporate.walmart.com/about/chile'
    company_logo: Walmart_logo
    location: Santiago, Chile
    date_start: '2017-11-17'
    date_end: '2018-10-01'
    description: |2-
        * Gave answers to business questions from Walmart merchants and the marketing team by integrating multiple data sources with R and SQL, and by applying statistical modelling, econometrics and data visualisation techniques.
      * Automated ad-hoc reports by using parametrised R Markdown documents.
      * Improved the impact evaluation of key company decisions by incorporating causal inference methodologies in otherwise descriptive analyses.

design:
  # background:
  #   # Name of image in `assets/media/`.
  #   image: background4.jpg
  #   # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  #   image_darken: 0.2
  #   #  Options are `cover` (default), `contain`, or `actual` size.
  #   image_size: cover
  #   # Options include `left`, `center` (default), or `right`.
  #   image_position: center
  #   # Use a fun parallax-like fixed background effect on desktop? true/false
  #   image_parallax: true
  #   # Text color (true=light, false=dark, or remove for the dynamic theme color).
  #   text_color_light: true
  columns: '2'
---
