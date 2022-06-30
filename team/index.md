---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Current Members

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
  filters="role: instructor"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pra"
%}

{:.center}

{% include section.html %}
- **Alumni**
  - Marie Mutryn<br>
  Senior Professional Research Assistant<br>
  Currently: Pfizer
  - Keith Strand<br>
  Postdoc<br>
  Currently: Senior Scientist at Pfizer
  - Henrick Horita<br>
  Postdoc<br>
  Currently: Marketing and Sales Manager at Cytoskeleton, Inc
  - Allison Ostriker<br>
  Graduate Student<br>
  Currently: Associate Research Scientist at Yale University

{% include section.html background="images/background.jpg" dark=true%}

We are recruiting! Please reach out to us if you are interested!

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="contact"
  style="button"
%}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="images/funding/nih-logo.svg"
  link1="https://www.nhlbi.nih.gov/"
  tooltip1="National Heart, Lung, and Blood Institute"

  image2="images/funding/cfret-logo.png"
  link2="https://medschool.cuanschutz.edu/consortium-for-fibrosis-research-translation"
  tooltip2="Consortium for Fibrosis Research and Translation"

  image3="images/funding/chernowitz-logo.png"
  link3="https://www.chernowitz.org/"
  tooltip3="Chernowitz Medical Research Foundation"
%}
