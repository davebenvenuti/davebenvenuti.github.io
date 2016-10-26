---
title: "Photography"
layout: single
author_profile: true
permalink: /photography
---

{% for photo in site.photos %}
 <a href="{{ photo.flickr_url }}" boner="wat">
    ![{{ photo.name }}]({{ photo.src }})
 </a>
{% endfor %}

