---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

I am part of Northwestern University's Center for Genetic Medicine

{%
  include link.html
  type="email"
  icon=""
  text="tanner.monroe@northwestern.edu"
  tooltip=""
  link="tanner.monroe@northwestern.edu"
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text="(210) 861-7888"
  tooltip=""
  link="+1-210-861-7888"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Robert+H.+Lurie+Medical+Research+Center+of+Northwestern+University,+303+E+Superior+St,+Chicago,+IL+60611/@41.8954479,-87.6196398,17z/data=!3m1!4b1!4m6!3m5!1s0x880fd3554999a93b:0x779532662251a102!8m2!3d41.8954479!4d-87.6196398!16s%2Fg%2F12hrghtdl"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

303 E. Superior 
Chicago, IL  
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/summer.png"
  caption="Summertime Chicago"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/winter.png"
  caption="Not summer"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
