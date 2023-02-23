---
title: Home
---

# Climb every mountain, ford every stream, follow every rainbow, 'til you find your dream.

I am a geneticist dedicated to understanding how human genetic variation influences cardiac form and function. I specialize in the design and implementation of tractable experiments that test hypotheses generated from personal and population genetics observations. This approach sorts into three primary areas of investigation:

{%
  include link.html
  type="github"
  icon=""
  text="See the template on GitHub"
  link="greenelab/lab-website-template"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

<div style="text-align: left;">
  <ul>
    <li><strong>Using statistical approaches to identify candidate deleterious variants.</strong> Rationally designed drugs with a strong basis in human genetics have repeatedly been proven to be more likely to gain FDA approval. Therefore, I focus my attention on discovering novel genetic components of disease. My approach is to identify highly penetrant variants passed down within families, and separately, look for inflation of common variants in more common diseases. I am keenly interested in how rare and common genetic variants interact to modify disease presentation, and how cumulative genetic burden amounts to a continuum of causality.</li>
  </ul>

  {% include link.html
    link="research"
    text="See what we've published"
    icon="fas fa-arrow-right"
    flip=true
  %}
</div>



{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
<li><strong>Testing the pathogenicity of those candidates.</strong> Of course, statistical inference is not enough to infer pathogenicity of novel loci. The early days of human genetics were fraught with imperfect assumptions about causality and genetic misattributions. Therefore, a critical component of my work is validation of candidate alleles. Usually, this means using animal models, or more recently, human-engineered tissues. All models are imperfect, so each decision is based on careful consideration of the appropriateness of the validation system. My preferred approach is to use orthogonal models and assay for convergent lines of evidence.</li>

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
<li><strong>Using that knowledge to more clearly understand disease-causing mechanisms.</strong> Once we identify a candidate variant and test whether or not it is pathogenic, the next step is to understand why. Even pathogenic variants within the same gene can have divergent molecular consequences. Pathogenicity within one gene can range from loss-of-function to overexuberance, or even deviant neofunctionalization. Therefore, in order to understand the genesis and course of disease, it is critical to understand the proximal molecular consequences stemming from mutation.</li>

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

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
