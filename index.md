---
title: Home
---

# Laboratory of Bioinformatics and Molecular Genetics

Bioinformatics enthusiats are welcome!

{%
  include link.html
  type="github"
  icon=""
  text="BMG Lab on Github"
  link="BMGLab"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See us at our University"
  link="https://biyomuhendislik.ege.edu.tr/"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
We work with all types of biological data. We aim to develop, test and share new bioinformatics algorithms. 
{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
Our Tools etc. etc. etc.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
Meet our team!

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
