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

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/bird2.png' | relative_url }}" alt="bird">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/bleak.png' | relative_url }}" alt="bleak">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/beach2.png' | relative_url }}" alt="beach">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/eternal.png' | relative_url }}" alt="eternal">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/hike.png' | relative_url }}" alt="hike">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/tass.png' | relative_url }}" alt="tazzy">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/building.png' | relative_url }}" alt="building">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/house.png' | relative_url }}" alt="house">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/tree.png' | relative_url }}" alt="tree">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/pole.png' | relative_url }}" alt="pole">
  </div>

  <div class="photo-item">
    <img src="{{ '/assets/images/portfolio/ivy.jpg' | relative_url }}" alt="ivy">
  </div>
</div>

