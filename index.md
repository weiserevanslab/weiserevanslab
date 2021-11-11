---
title: Home
---

# Welcome to the Weiser-Evans Laboratory
Our group is interested in the study of

{:.center}

{% include section.html %}

# Recent Highlights

{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

[See what we've published &nbsp;→](research)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/AngII_AO_100x_a.jpg"
  link="research"
  headline="Our Research"
  text=text
%}

{% capture text %}
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

[See what we do &nbsp;→](publications)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/publications/atvblargecover.jpg"
  link="publications"
  headline="Our Publications"
  text=text
%}

{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

[Meet our team &nbsp;→](team)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/team/labphoto.jpg"
  link="team"
  headline="Our Team"
  text=text
%}
