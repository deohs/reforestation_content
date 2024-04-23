---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Etiquetas / Labels
---

<div class="intro">
  <div class="intro-text">
    <p>Información de salud y seguridad de las 40 etiquetas principales de herbicidas utilizados en el manejo de vegetación forestal en Oregón y el estado de Washington.</p>
    <h3>Estas traducciones son solo para información. La etiqueta es la ley.</h3>

    <p><hr /></p>

    <p>Health and Safety information from 40 top labels for Oregon and Washington herbicides used in forestry vegetation management.</p>
    <h3>These translations are for information only. The label is the law.</h3>
  </div>

  <div class="sponsor-logos">
    <a href="https://deohs.washington.edu/pnash/" target="_blank"><img src="{{ "/img/PNASH-logo-web-150ppi-sq.png" | relative_url }}" alt="PNASH" /></a>
    <a href="https://www.washington.edu/" target="_blank"><img src="{{ "/img/W-Logo_Purple_Hex_sq.png" | relative_url }}" alt="UW" /></a>
    <a href="https://www.wsu.edu/" target="_blank"><img src="{{ "/img/WSU.jpg" | relative_url }}" alt="WSU" /></a>
    <a href="https://www.oregonstate.edu/" target="_blank"><img src="{{ "/img/OSU.jpg" | relative_url }}" alt="OSU" /></a>
    <a href="https://osha.oregon.gov/" target="_blank"><img src="{{ "/img/Oregon-OSHA-logo-blue.jpg" | relative_url }}" alt="OR OSHA" /></a>
  </div>
</div>

{% assign labels = site.label_pages | sort_natural: "title" %}
{% for label in labels %}
  <h3><a href="{{ label.url | relative_url }}">{{ label.title }}</a></h3>
{% endfor %}

<div>
  Spanish translations/Traducciones al español <img src="{{ "/img/52px-Cc.logo.circle.png" | relative_url }}" alt="CC" class="cc-mark" /> BY-NC-SA 4.0 The State of Washington 2024
</div>
