---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---
**Some Glimpse of Advancements in AGN, Galaxy Cluster and IGM Research Conference**

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
