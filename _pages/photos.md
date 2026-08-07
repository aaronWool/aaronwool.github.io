---
layout: page
title: photos
permalink: /photos/
description: Restored profile and travel portfolio from the previous site.
nav: true
nav_order: 5
---

<style>
  .photo-masonry {
    column-count: 3;
    column-gap: 1rem;
  }

  .photo-masonry-item {
    break-inside: avoid;
    margin-bottom: 1rem;
  }

  .photo-masonry-item figure {
    margin: 0;
  }

  .photo-masonry-item img {
    width: 100%;
    height: auto;
    display: block;
  }

  @media (max-width: 900px) {
    .photo-masonry {
      column-count: 2;
    }
  }

  @media (max-width: 576px) {
    .photo-masonry {
      column-count: 1;
    }
  }
</style>

<div class="photo-gallery">
  <div class="photo-masonry">
    <div class="photo-masonry-item">
      {% include figure.liquid path="assets/img/profile/profile.jpg" title="Profile portrait" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="photo-masonry-item">
      {% include figure.liquid path="assets/img/portfolio/travel/israel.jpg" title="ECCV 2022 Israel" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="photo-masonry-item">
      {% include figure.liquid path="assets/img/portfolio/travel/quebec.jpg" title="Quebec" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="photo-masonry-item">
      {% include figure.liquid path="assets/img/portfolio/travel/fort-henry.jpg" title="Fort Henry" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="photo-masonry-item">
      {% include figure.liquid path="assets/img/portfolio/travel/thousand-islands.jpg" title="Thousand Islands" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="photo-masonry-item">
      {% include figure.liquid path="assets/img/portfolio/travel/western.png" title="Western University" class="img-fluid rounded z-depth-1" %}
    </div>
  </div>
</div>

<div class="row">
  <div class="col-md-6 mt-4">
    <iframe src="https://720yun.com/vr/0ed21ap59c6" title="Quebec panorama" loading="lazy" style="width: 100%; min-height: 420px; border: 1px solid var(--global-divider-color); border-radius: 4px;"></iframe>
  </div>
  <div class="col-md-6 mt-4">
    <iframe src="https://720yun.com/vr/6f720apfj1w" title="Thousand Islands panorama" loading="lazy" style="width: 100%; min-height: 420px; border: 1px solid var(--global-divider-color); border-radius: 4px;"></iframe>
  </div>
  <div class="col-md-6 mt-4">
    <iframe src="https://720yun.com/vr/bce20xpkjlr" title="Western University panorama" loading="lazy" style="width: 100%; min-height: 420px; border: 1px solid var(--global-divider-color); border-radius: 4px;"></iframe>
  </div>
  <div class="col-md-6 mt-4">
    <iframe src="https://www.youtube-nocookie.com/embed/xmnM8VjSzUY" title="Quebec city center" loading="lazy" allowfullscreen style="width: 100%; aspect-ratio: 16 / 9; border: 0;"></iframe>
    <iframe src="https://www.youtube-nocookie.com/embed/GABJUxp5P90" title="Fairmont Le Chateau Frontenac" loading="lazy" allowfullscreen style="width: 100%; aspect-ratio: 16 / 9; border: 0; margin-top: 1rem;"></iframe>
  </div>
</div>
