---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

We work with a variety of people and disciplines.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

## Join

#### Researchers (Ph.D Student / M.Sc Student)

Bioinformatics enthusiasts are welcome

- Basic level of coding (R - Python - Bash)
- Previous experience in NGS - ML - HPCC are always a plus

{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="iamges/TÜBİTAK_logo.png"
  link1="https://www.tubitak.gov.tr/"
  tooltip1="TUBITAK"

  image2="images/cost.png"
  link2="https://www.cost.eu/"
  tooltip2="COST ACTION"

  image3="images/tüseb.png"
  link3="https://www.tuseb.gov.tr/"
  tooltip3="TÜSEB"

%}
