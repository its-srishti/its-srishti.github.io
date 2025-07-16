---
layout: collection
title: "Favourites"
permalink: /favourites/
classes: wide
---

{% assign sections = site.data.favourites %}

{% include favourites-section.html section="📚 Books" emoji="📚" items=sections.books %}
{% include favourites-section.html section="🎥 Movies" emoji="🎥" items=sections.movies %}
{% include favourites-section.html section="☕ Beverages" emoji="☕" items=sections.beverages %}
{% include favourites-section.html section="💬 Quotes" emoji="💬" items=sections.quotes %}
{% include favourites-section.html section="🎵 Music" emoji="🎵" items=sections.music %}
{% include favourites-section.html section="🎨 Art" emoji="🎨" items=sections.art %}
{% include favourites-section.html section="✈️ Travel" emoji="✈️" items=sections.travel %}
