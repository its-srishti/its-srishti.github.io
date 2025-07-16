---
layout: single
title: "Favourites"
permalink: /favourites/
classes: wide
---

<style>
.fav-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}
.fav-card {
  background-color: #1e1e1e;
  border-radius: 15px;
  padding: 1rem;
  text-align: center;
  box-shadow: 0 6px 12px rgba(0,0,0,0.2);
  color: #fff;
}
.fav-card img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 1rem;
}
.fav-card .title {
  font-size: 1.2rem;
  font-weight: bold;
  margin-bottom: 0.5rem;
}
.fav-card .desc {
  font-size: 0.9rem;
  opacity: 0.85;
}
</style>

<div class="fav-grid">
  <div class="fav-card">
    <img src="/assets/images/favourites/ikigai.jpg" alt="Ikigai">
    <div class="title">Ikigai</div>
    <div class="desc">A Japanese concept meaning “a reason for being.”</div>
  </div>

  <div class="fav-card">
    <img src="/assets/images/favourites/dps.jpg" alt="Dead Poets Society">
    <div class="title">Dead Poets Society</div>
    <div class="desc">“Carpe Diem.” A film that redefined purpose and poetry.</div>
  </div>

  <div class="fav-card">
    <img src="/assets/images/favourites/immortal-talks.jpg" alt="Immortal Talks">
    <div class="title">Immortal Talks</div>
    <div class="desc"><a href="https://www.amazon.in/dp/B086WPTG5M" target="_blank" rel="noopener">Buy on Amazon</a></div>
  </div>

  <!-- Add more manually here -->
</div>
