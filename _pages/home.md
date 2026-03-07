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


You can find find my resume [here]({{ base_path }}/cv/). 

Please, do not hesitate to reach out and/or connect.  


## Recent Posts

{% for post in site.posts limit:3 %}
<div class="recent-post-row">
  <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
  <a href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}

