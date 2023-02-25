---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

There is no "I" in team. But for now, it's just me

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
  filters="role: phd"
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

#### Technician jobs available soon

Be my other seet of hands! I'll need someone with the following skillset:

- Attention to detail
- Obsessive sterile technique
- Curiosity

#{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
#{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
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
