---
layout: page
title: Gallery
permalink: /gallery/
description: Some photos I took in the lab over the years
nav: true
nav_order: 4
---


<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Masonry Gallery with Zoom</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Lightbox CSS -->
  <link href="https://cdn.jsdelivr.net/npm/lightbox2@2/dist/css/lightbox.min.css" rel="stylesheet">

  <style>
    .masonry {
      column-count: 3;              /* FIXED */
      column-gap: 1rem;
    }

    .masonry a {
      display: block;
      margin-bottom: 1rem;
      break-inside: avoid;
    }

    .masonry img {
      width: 100%;
      border-radius: 8px;
    }

    @media (max-width: 768px) {
      .masonry { column-count: 2; }
    }

    @media (max-width: 576px) {
      .masonry { column-count: 1; }
    }
  </style>
</head>

<body>

<div class="container-fluid px-3 mt-4">  <!-- FIXED -->
  <div class="masonry">

    <a href="../assets/IMG-20210215-WA0000.jpeg" data-lightbox="gallery">
      <img src="../assets/IMG-20210215-WA0000.jpeg" class="img-fluid rounded">
    </a>

    <a href="../assets/IMG-20220925-WA0000.jpg" data-lightbox="gallery">
      <img src="../assets/IMG-20220925-WA0000.jpg" class="img-fluid rounded">
    </a>

    <a href="../assets/IMG-20240125-WA0000.jpg" data-lightbox="gallery">
      <img src="../assets/IMG-20240125-WA0000.jpg" class="img-fluid rounded">
    </a>

    <a href="../assets/IMG-20241031-WA0001.jpg" data-lightbox="gallery">
      <img src="../assets/IMG-20241031-WA0001.jpg" class="img-fluid rounded">
    </a>

    <a href="../assets/IMG_20230530_165541_979.jpg" data-lightbox="gallery">
      <img src="../assets/IMG_20230530_165541_979.jpg" class="img-fluid rounded">
    </a>

        <a href="../assets/IMG_20240613_165804_221.jpg" data-lightbox="gallery">
      <img src="../assets/IMG_20240613_165804_221.jpg" class="img-fluid rounded">
    </a>
    
  </div>
</div>

<!-- Lightbox JS -->
<script src="https://cdn.jsdelivr.net/npm/lightbox2@2/dist/js/lightbox.min.js"></script>

</body>
</html>


