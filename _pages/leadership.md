---
title: "Leadership & Extra-Curricular Involvement"
excerpt: ""
author_profile: true
permalink: /leadership/
redirect_from: 
  - /about.html
---
## Volunteering Experience

<div align="center">
  <div class="container">
    <div class="header">
      <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/gnsfLogo.jpg" alt="GNSF Logo" class="logo">
      <div>
        <p class="title">Greater Noakhali Students Forum, CUET</p>
        <p class="position">📌Vice President</p>
        <p class="duration">Jun 2023 - Aug 2024 | 1 yr 2 mos</p>
        <p class="position">📌Joint Literature Secretary</p>
        <p class="duration">Jun 2022 - Jun 2023 | 1 yr</p>
        <p class="position">📌Executive Member</p>
        <p class="duration">April 2019 - June 2022 | 3 yr 2 mos</p>
      </div>
    </div>

    <div class="carousel-container">
      <div id="carousel" class="carousel">
        <div class="slide">
          <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/gnsfAGM.jpeg" alt="img2" class="slide-image">
          <div class="caption">Token of Appreciation in Annual General Meeting 2024</div>
        </div>
        <div class="slide">
          <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/gnsf.png" alt="img1" class="slide-image">
          <div class="caption">GNSF Executive Committee 2023</div>
        </div>
        <!-- Add more images below -->
        <div class="slide">
          <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/gnsfAdmission2.JPG" alt="img3" class="slide-image">
          <div class="caption">A part of GNSF family in CUET Admission Event 2023</div>
        </div>
        <div class="slide">
          <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/gnsfIftar1.jpg" alt="img4" class="slide-image">
          <div class="caption">GNSF Iftar Mahfil 2023</div>
        </div>
        <div class="slide">
          <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/gnsfIftar2.jpg" alt="img5" class="slide-image">
          <div class="caption">GNSF Iftar Mahfil 2023</div>
        </div>
      </div>
      <a href="javascript:void(0)" onclick="slide(-1)" class="nav-button left">&#10094;</a>
      <a href="javascript:void(0)" onclick="slide(1)" class="nav-button right">&#10095;</a>
    </div>
  </div>
</div>



<style>
  .container {
    border: 2px solid #e1e4e8;
    border-radius: 10px;
    padding: 20px;
    max-width: 100%;
    margin: auto;
    box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
    background-color: #fff;
  }

  .header {
    display: flex;
    align-items: center
    justify-content: center;
    margin-bottom: 20px;
  }

  .logo {
    width: 100px;
    height: auto;
    margin-right: 20px;
  }

  .title
  {
    margin: 0;
    font-size: 2.5em;
    text-align: left;
    font-weight: bold;
  }

  .position {
    margin: 5px 0;
    font-size: 1.2em;
    text-align: left;
    font-weight: bold;
  }

  .duration {
    margin: 0;
    color: #6a737d;
    font-size: 1.0em;
    text-align: left;
    font-style: italic;
  }

  .carousel-container {
    position: relative;
    width: 100%;
    overflow: hidden;
    border-radius: 10px;
    height: 600px; /* Increased height to allow larger images */
  }

  .carousel {
    display: flex;
    transition: transform 0.5s ease;
  }

  .slide {
    flex: 0 0 100%;
    text-align: center;
    position: relative;
  }

  .slide-image {
    width: 100%;
    height: auto;
    object-fit: contain;
    max-height: 550px; /* Increased max-height for larger images */
    border-radius: 10px;
  }

  .caption {
    background: rgba(0, 0, 0, 0.5);
    color: #fff;
    width: 100%;
    text-align: center;
    padding: 10px;
    margin-top: 10px;
  }

  .nav-button {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    text-decoration: none;
    font-size: 24px;
    color: #fff;
    background-color: rgba(0,0,0,0.5);
    padding: 10px;
    border-radius: 50%;
  }

  .nav-button.left {
    left: 10px;
  }

  .nav-button.right {
    right: 10px;
  }
</style>

<script>
  let currentIndex = 0;
  const images = document.querySelectorAll('#carousel > .slide');
  const totalImages = images.length;

  function showImages() {
    const offset = -currentIndex * 100;
    document.getElementById('carousel').style.transform = `translateX(${offset}%)`;
  }

  function slide(step) {
    currentIndex = (currentIndex + step + totalImages) % totalImages;
    showImages();
  }
</script>



