---
title: "Florentin Rochet - Publications"
layout: gridlay
excerpt: "Florentin Rochet -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## 2020

{% for publi in site.data.publist %}
  {% if publi.year == 2020 %}
  <b>{{ publi.title }} </b><br />
  <em>{{ publi.authors }} </em><br />
  In:<em> {{ publi.in }} </em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}
{% endfor %}

## 2019

{% for publi in site.data.publist %}
  {% if publi.year == 2019 %}
  <b>{{ publi.title }} </b><br />
  <em>{{ publi.authors }} </em><br />
  In:<em> {{ publi.in }} </em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}
{% endfor %}

## 2018

{% for publi in site.data.publist %}
  {% if publi.year == 2018 %}
  <b>{{ publi.title }} </b><br />
  <em>{{ publi.authors }} </em><br />
  In:<em> {{ publi.in }} </em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}
{% endfor %}

## 2017

{% for publi in site.data.publist %}
  {% if publi.year == 2017 %}
  <b>{{ publi.title }} </b><br />
  <em>{{ publi.authors }} </em><br />
  In:<em> {{ publi.in }} </em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}
{% endfor %}


