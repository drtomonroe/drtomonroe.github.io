---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <img src="heart_icon.png" alt="Research" style="width: 40px; height: 50px; margin-right: 10px; vertical-align: middle;">Team


There is no "I" in team, but for now it's just me

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: Cheerleader"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: student"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: staff"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}


{% include section.html %}

## Join

#### Technician jobs available soon

Be my other set of hands! I'll need someone with the following skillset:

- Attention to detail
- Obsessive sterile technique
- Curiosity

{% include section.html %}

## Funding

Our work is made possible by past or present funding from these organizations
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/aha.png"
  link1="https://www.heart.org"
  tooltip1="Cool Foundation"

  image2="images/nih.png"
  link2="https://www.nih.gov"
  tooltip2="Cool Institute"

%}
