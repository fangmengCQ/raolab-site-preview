---
---

# Homepage of Yu RAO's Lab

Yu RAO's lab focuses on a variety of disease areas, including malignancies, infectious diseases, and age-related degenerative diseases. 

{% include section.html %}

## Highlights

{% capture text %}

Our main research directions are as follows:

Development of small molecule-based targeted protein degradation technologies (such as PROTACs and molecular glues) for targeted protein degradation and related drug development.

Design, synthesis, and development of small molecule compounds for the treatment of cancer and infectious diseases, based on the three-dimensional structures of target proteins.

Chemical synthesis of biologically active small molecules and their application as molecular probes in chemical biology research.

Through these efforts, we aim to advance therapeutic strategies and deepen our understanding of disease mechanisms at the molecular level.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

<!-- {% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %} -->

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

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
