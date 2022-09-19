---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: hero # See https://wowchemy.com/docs/page-builder/
headless: true # This file represents a page section.
weight: 10 # Order that this section will appear.
title: |
  Occupational Prestige  
  Research Group
hero_media: welcome.jpg
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
  # Add custom styles
  css_style:
  css_class:
---

<br>

At the **Occupational Research Group**, we collect and maintain data about the prestige of O*NET occupations. 

The purpose of this website is to provide all of the necessary materials and data needed to measure individual's occupational prestige, the status component of socioeconomic status (SES). We recommend that researchers use the csv provided to create a dropdown item in Qualtrics that participants  use to indicate their occupation and occupational family. The output from this item is a list of participants occupations that can be scored using the csv of the ratigs and a simple line of code in R --- i.e., left_join(qualtrics_data, op_ratings.csv, by = occupation_title

To access these files, and crosswalks with older occupational prestige indices, click on "Go to Prestige Data"
