---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

{% include base_path %}

<div class="gallery-grid">

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/1831886a-5f27-444c-8c6f-a3ad77ace984.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/40f4a934-d811-4f46-a1dc-e3176d6aab32.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/9a952581-2eb0-4e21-aa24-467ede9ba8f7.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/fe9b95f0-d954-48c4-941f-42c33c0996ea.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/IMG_6911.JPG" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/IMG_7265.JPG" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/IMG_7267.JPG" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/IMG_3796.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/IMG_3854.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/IMG_4179.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/IMG_4331.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/IMG_4366.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/732caf14-514e-41ba-8c7e-04a8b74a3ed0.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

  <figure class="gallery-item">
    <div class="gallery-img-wrap"><img src="/images/gallery/032af147-af15-4927-9768-3fd48c7bd9cf.jpg" alt="" loading="lazy"></div>
    <figcaption class="gallery-caption">Add a caption here.</figcaption>
  </figure>

</div>

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
  gap: 1.25rem;
  margin: 1.5rem 0;
}
.gallery-item {
  margin: 0;
  background: #fff;
  border: 1px solid #e6e9ee;
  border-radius: 12px;
  overflow: hidden;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.gallery-item:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 26px rgba(20,33,59,0.12);
}
.gallery-img-wrap {
  width: 100%;
  aspect-ratio: 4 / 3;
  overflow: hidden;
  background: #f2f6fc;
}
.gallery-img-wrap img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform 0.3s ease;
}
.gallery-item:hover .gallery-img-wrap img { transform: scale(1.04); }
.gallery-caption {
  padding: 0.7rem 0.9rem;
  font-size: 0.85rem;
  line-height: 1.4;
  color: #2a3346;
  font-weight: 500;
  text-align: center;
}

@media (max-width: 600px) {
  .gallery-grid { grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 0.8rem; }
  .gallery-caption { font-size: 0.78rem; padding: 0.55rem 0.6rem; }
}
</style>
