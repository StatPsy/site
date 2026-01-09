---
---

# StatPsy's Website

We study the cognitive architecture of the language production and comprehension systems and their links with other cognitive functions using a variety of methods and measurements: response times, eye-tracking, EEG, corpus data.

We have a dedicated interest in applied statistics (machine learning, bayesian models, linear mixed-effects models, etc.) and attach great importance to open science practices. We do our best to use available tools, inculding pre-registration, power-analyses, sharing of data and code.

{% include section.html %}

## Highlights

{% capture text %}

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="publications"
  title="Our Research"
  text=text
%}

{% capture text %}

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
