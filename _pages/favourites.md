---
layout: collection
title: "Favourites"
permalink: /favourites/
collection: favourites
entries_layout: grid
classes: favourites-page
---

{% assign favs = site.favourites | sort: 'date' %}

## 📚 Books
{% assign books = site.favourites | where:"category","books" %}
{% for item in books %}
  {% include archive-single.html item=item %}
{% endfor %}

## 🎥 Movies
{% assign movies = site.favourites | where:"category","movies" %}
{% for item in movies %}
  {% include archive-single.html item=item %}
{% endfor %}

## ☕ Beverages
{% assign beverages = site.favourites | where:"category","beverages" %}
{% for item in beverages %}
  {% include archive-single.html item=item %}
{% endfor %}


## 📚 Quotes
{% assign books = site.favourites | where:"category","quotes" %}
{% for item in books %}
  {% include archive-single.html item=item %}
{% endfor %}

## 🎥 Art
{% assign movies = site.favourites | where:"category","art" %}
{% for item in movies %}
  {% include archive-single.html item=item %}
{% endfor %}

## ☕ Travel
{% assign beverages = site.favourites | where:"category","travel" %}
{% for item in beverages %}
  {% include archive-single.html item=item %}
{% endfor %}

