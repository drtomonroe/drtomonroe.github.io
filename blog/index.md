---
title: News
nav:
  order: 4
  tooltip: Musings and miscellany
---

# What's happening

{% include section.html %}

{% include search-info.html %}

{% assign coll = site.posts %}
<ul class="post-list">
  {% for item in coll %}
    <li class="post-list-item">
      <h3 class="post-title">
        <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      </h3>
      <div class="post-excerpt">
        {{ item.excerpt | markdownify }}
      </div>
      <p class="post-meta">
        <a href="{{ item.url | relative_url }}">Read more →</a>
      </p>
    </li>
  {% endfor %}
</ul>

{% include section.html %}

## Twitter

<!-- Twitter embeds from https://publish.twitter.com/ -->

<a class="twitter-timeline" data-width="400" data-height="400" href="https://twitter.com/TannerOMonroe">Tweets by TannerOMonroe</a> 
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{:.center}

<a href="https://twitter.com/TannerOMonroe" class="twitter-follow-button" data-show-count="false">Follow @TannerOMonroe</a>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<a href="https://twitter.com/TannerOMonroe" class="twitter-mention-button" data-show-count="false">Tweet to @TannerOMonroe</a>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{:.center}
