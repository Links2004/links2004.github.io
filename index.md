---
layout: page
title: Tech Projects
#tagline: Supporting tagline
---
{% include JB/setup %}

Home of all my Projects

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


## Arduino for ESP
  
 [more @ GitHub](https://github.com/esp8266/Arduino){:target="_blank"}
 
<hr />
 
## Arduino VNC

a VNC Client for Arduino based on rfbproto.

<iframe width="360" height="640" src="https://www.youtube.com/embed/MA47npOtApc?VQ=HD720" frameborder="0" allowfullscreen></iframe>

[more @ GitHub](https://github.com/Links2004/arduinoVNC){:target="_blank"}

<hr />

## Arduino WebSockets


### Supported Hardware
 - ESP8266 [Arduino for ESP8266](https://github.com/Links2004/Arduino){:target="_blank"}
 - ATmega328 with Ethernet Shield (alpha)
 - ATmega328 with enc28j60 (alpha)
 - ATmega2560 with Ethernet Shield (alpha)
 - ATmega2560 with enc28j60 (alpha)
 
 [more @ GitHub](https://github.com/Links2004/arduinoWebSockets){:target="_blank"}
 
<hr />
 


