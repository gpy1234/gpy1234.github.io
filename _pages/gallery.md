---
layout: page
permalink: /gallery/
title: gallery
description: Different Photos
nav: true
nav_order: 5
---
<style>
  .image-row {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
  }
  .image-row div {
    width: 30%; /* Adjust this if you need */
    text-align: center;
  }
  .image-row img {
    width: 100%;
    object-fit: cover;
    border-radius: 8px; /* optional for rounded corners */
  }
</style>

<div class="image-row">
  <div>
    <img src="../images/images (1).jpeg" alt="Description 1" />
    <p>Description 1</p>
  </div>
  <div>
    <img src="../images/download.jpeg" alt="Description 2" />
    <p>Description 2</p>
  </div>
  <div>
    <img src="../images/images (2).jpeg" alt="Description 3" />
    <p>Description 3</p>
  </div>
</div>
