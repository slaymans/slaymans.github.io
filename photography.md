---
layout: page
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

  <!-- Photo 1 -->
  <div class="photo-item">
    <img src="{{ site.url }}/assets/portfolio/bird2.png" alt="A shot of bird2">
  </div>

  <!-- Photo 2 -->
  <div class="photo-item">
    <img src="{{ site.url }}/assets/portfolio/bleak.png" alt="A shot of bleak">
  </div>
  
  <!-- Photo 3 -->
  <div class="photo-item">
    <img src="{{ site.url }}/assets/portfolio/beach2.png" alt="A shot of beach2">
  </div>

</div>

