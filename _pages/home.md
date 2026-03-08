---
permalink: /
title: "Home"
author_profile: true
redirect_from: 
  - /home/
  - /home.html
hide_title: true
---

# Hi, I am Amine El Ouassouli. 

## Site under construction ⚒️ 🚧


You can find my resume [here]({{ base_path }}/cv/). 

Please, do not hesitate to reach out by email and/or connect on the usual plateforms 🙏


## Recent Posts

{% for post in site.posts limit:3 %}
<div class="recent-post-row">
  <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
  <a class="post-title-link" href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}

