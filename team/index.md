---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <img src="heart_icon.png" alt="Research" style="width: 45px; height: 50px; margin-right: 10px; vertical-align: middle;">Team


# We are recruiting at all levels. 

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: Me"
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

#### The LXCG is recruiting technicians, students, and postdoctoral researchers!

We welcome candidates with evidence of high-level scholarship and technical expertise from diverse quantitative and experimental backgrounds commensurate with their role. Those with experience in DNA sequencing analysis and/or hiPSC-derived cardiomyocyte culture are particularly encouraged to apply.

We prioritize intellectual curiosity, rigorous mechanistic thinking, and personalized mentorship. We are housed in the Cardiovascular Research Institute – a highly collaborative ecosystem deliberately structured to foster opportunities for cross-disciplinary research focused on the heart.

Interested candidates should email a cover letter and CV to Dr. Monroe at [tanner.monroe@mssm.edu](mailto:tanner.monroe@mssm.edu).




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
