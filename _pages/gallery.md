---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true

---

<hr>

<h2>Some Glimpse of Observing the Wonders of Nature: From Camera Obscura to the 4-m International Liquid Mirror Telescope (ILMT)</h2>
<div class="gallery">
  <img src="/images/lensing_school/1.jpeg" onclick="openModal(this)">
  <img src="/images/lensing_school/2.jpeg" onclick="openModal(this)">
  <img src="/images/lensing_school/3.jpeg" onclick="openModal(this)">
</div>

<hr>



<hr>

<h2>Some Glimpse of Multiwavelength study of AGN central engine, and its environment</h2>
<div class="gallery">
  <img src="/images/agn_central_engine/1.jpeg" onclick="openModal(this)">
  <img src="/images/agn_central_engine/2.jpeg" onclick="openModal(this)">
  <img src="/images/agn_central_engine/3.jpeg" onclick="openModal(this)">
</div>

<hr>

<h2>Some Glimpse of Himalayan Meet of Astronomers (HMA) - 2024</h2>
<div class="gallery">
  <img src="/images/HMA_2024/1.png" onclick="openModal(this)">
  <img src="/images/HMA_2024/2.png" onclick="openModal(this)">
</div>

<hr>

<h2>Some Glimpse of Advancements in AGN, Galaxy Cluster and IGM Research Conference</h2>

<style>
  .gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
  }
  .gallery img {
    max-width: 100%;
    height: auto;
    margin: 10px;
    flex: 1 1 20%;
    box-sizing: border-box;
    cursor: pointer;
  }
  .modal {
    display: none;
    position: fixed;
    z-index: 1;
    padding-top: 60px;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgb(0,0,0);
    background-color: rgba(0,0,0,0.9);
  }
  .modal-content {
    margin: auto;
    display: block;
    width: 80%;
    max-width: 700px;
  }
  .close {
    position: absolute;
    top: 15px;
    right: 35px;
    color: #fff;
    font-size: 40px;
    font-weight: bold;
    transition: 0.3s;
  }
  .close:hover,
  .close:focus {
    color: #bbb;
    text-decoration: none;
    cursor: pointer;
  }
</style>



<div class="gallery">
  <img src="/images/conff_images/6.jpeg" alt="image1" onclick="openModal(this)">
  <img src="/images/conff_images/7.jpeg" alt="image2" onclick="openModal(this)">
  <img src="/images/conff_images/4.jpeg" alt="image3" onclick="openModal(this)">
  <img src="/images/conff_images/1.jpeg" alt="image6" onclick="openModal(this)">
</div>

<div id="myModal" class="modal">
  <span class="close" onclick="closeModal()">&times;</span>
  <img class="modal-content" id="modalImage">
</div>

<script>
  function openModal(img) {
    var modal = document.getElementById("myModal");
    var modalImg = document.getElementById("modalImage");
    modal.style.display = "block";
    modalImg.src = img.src;
  }

  function closeModal() {
    var modal = document.getElementById("myModal");
    modal.style.display = "none";
  }
</script>

<hr>

<hr>

<h2>Some Glimpse of Space Day celebration (1 month event)</h2>
<div class="gallery">
  <img src="/images/space_day/1.jpg" onclick="openModal(this)">
  <img src="/images/space_day/2.jpg" onclick="openModal(this)">
  <img src="/images/space_day/3.jpg" onclick="openModal(this)">
</div>

<h2>Some Glimpse of Beginning Astronomy v2: Start a data-driven journey</h2>

<div class="gallery">
  <img src="/images/data_driven_astrophysics/1.jpeg" onclick="openModal(this)">
  <img src="/images/data_driven_astrophysics/2.png" onclick="openModal(this)">
  <img src="/images/data_driven_astrophysics/3.png" onclick="openModal(this)">
</div>


<hr>

<h2>Some Glimpse of Exoplanet Workshop on Extra-solar Planets and the Search for Habitable Worlds</h2>
<div class="gallery">
  <img src="/images/exoplanet_workshop/1.png" onclick="openModal(this)">
  <img src="/images/exoplanet_workshop/2.png" onclick="openModal(this)">
  <img src="/images/exoplanet_workshop/3.png" onclick="openModal(this)">
  <img src="/images/exoplanet_workshop/4.png" onclick="openModal(this)">
</div>
