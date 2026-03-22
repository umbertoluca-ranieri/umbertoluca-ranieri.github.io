---
layout: page
title: Gallery2
permalink: /gallery2/
description: Some photos I took in the lab over the years...
nav: true
nav_order: 5
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
      column-count: 4;
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

    @media (max-width: 992px) {
      .masonry { column-count: 3; }
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

<div class="container mt-4">
  <div class="masonry">

    <a img src="../assets/img/3.jpg" data-lightbox="gallery">
      <img src="../assets/img/3.jpg" class="img-fluid rounded" alt="Image 1">
    </a>

    <a img src="../assets/img/5.jpg" data-lightbox="gallery">
      <img src="../assets/img/5.jpg" class="img-fluid rounded" alt="Image 1">
    </a>

    <a img src="../assets/img/2.jpg" data-lightbox="gallery">
      <img src="../assets/img/2.jpg" class="img-fluid rounded" alt="Image 1">
    </a>

    <a img src="../assets/img/1.jpg" data-lightbox="gallery">
      <img src="../assets/img/1.jpg" class="img-fluid rounded" alt="Image 1">
    </a>

  </div>
</div>

<!-- Lightbox JS -->
<script src="https://cdn.jsdelivr.net/npm/lightbox2@2/dist/js/lightbox.min.js"></script>

</body>
</html>



