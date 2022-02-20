---
published: false
layout: page
permalink: /twitter/index.html
title: Twitter
tweets:
  - https://twitter.com/dhh/status/1162426045405921282
  - https://twitter.com/rails/status/1205565185739673600
a_tweet: https://twitter.com/rubygems/status/518821243320287232
---
<div class='jekyll-twitter-plugin' align="center">
{% for tweet in page.tweets %}
  {% twitter tweet align=center width=350 %}
{% endfor %}
{% twitter page.a_tweet %}
{% twitter https://twitter.com/dhh maxwidth=500 limit=5 %}
</div>
