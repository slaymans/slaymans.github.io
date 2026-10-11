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

Welcome to my photography portfolio. A selection of my work is displayed below.

<div class="photo-grid">

  <!-- Try relative paths without a leading slash -->
  <div class="photo-item">
    <img src="assets/portfolio/bird2.png" alt="bird">
  </div>

  <div class="photo-item">
    <img src="assets/portfolio/bleak.png" alt="bleak">
  </div>
  
  <div class="photo-item">
    <img src="assets/portfolio/beach2.png" alt="beach">
  </div>

</div>
