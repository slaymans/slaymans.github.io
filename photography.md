---
layout: page
title: Photography
permalink: /photography/
---

<style>
  .photo-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 16px;
    margin-top: 20px;
  }
  .photo-item {
    aspect-ratio: 3/2;
    overflow: hidden;
    border-radius: 4px;
    background: #f0f0f0;
  }
  .photo-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    transition: transform 0.3s ease;
  }
  .photo-item:hover img {
    transform: scale(1.03);
  }
</style>

<div class="photo-grid">
  <div class="photo-item">
    <img src="{{ site.baseurl }}/assets/portfolio/beach2" alt="Description of photo 1">
  </div>
  <div class="photo-item">
    <img src="{{ site.baseurl }}/assets/portfolio/bleak" alt="Description of photo 2">
  </div>
  <div class="photo-item">
    <img src="{{ site.baseurl }}/assets/portfolio/bird2" alt="Description of photo 3">
  </div>
</div>