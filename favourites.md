---
layout: collection
title: "Favourites"
permalink: /favourites/
collection: favourites
entries_layout: grid
classes: wide
---

{% assign favs = site.favourites | sort: 'date' %}

<h2>📚 Books</h2>
<div class="archive">
  {% for item in favs %}
    {% if item.category == "Books" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>

<h2>🎥 Movies</h2>
<div class="archive">
  {% for item in favs %}
    {% if item.category == "Movies" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>

<h2>📚 Beverage</h2>
<div class="archive">
  {% for item in favs %}
    {% if item.category == "Beverage" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>

<h2>📚 Quotes</h2>
<div class="archive">
  {% for item in favs %}
    {% if item.category == "Quotes" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>

<h2>🎥 Travel</h2>
<div class="archive">
  {% for item in favs %}
    {% if item.category == "Travel" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>

<h2>📚 Art</h2>
<div class="archive">
  {% for item in favs %}
    {% if item.category == "Art" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>
