---
layout: page
title: Media Gallery
---
<ul>
{% for playlist in site.data.playlist %}
  <li>
    Song name:{{playlist.title}}
	Whatch at <a href="https:/youtube.com{{playlist.link}}"">
	Duration:{{playlist.duration}}
    
  </li>
{% endfor %}
</ul>