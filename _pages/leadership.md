---
title: "Leadership & Extra-Curricular Involvement"
excerpt: ""
author_profile: true
permalink: /Leadership & Extra-Curricular/
redirect_from: 
  - /about.html
---
## Volunteering Experience

<div align="center">
  <div style="border: 2px solid #e1e4e8; border-radius: 10px; padding: 20px; max-width: 600px; margin: auto; box-shadow: 0px 4px 8px rgba(0,0,0,0.1);">
    <div style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="Gallery/gnsfLogo.jpg" alt="GNSF Logo" style="width: 60px; height: auto; margin-right: 20px;">
      <div>
        <h3 style="margin: 0; font-size: 1.5em;">Vice President</h3>
        <p style="margin: 5px 0;">Greater Noakhali Students Forum, CUET</p>
        <p style="margin: 0; color: #6a737d;">Jun 2023 - Present | 1 yr 3 mos</p>
      </div>
    </div>
    
    <div style="position: relative; width: 100%; overflow: hidden;">
      <div id="carousel" style="display: flex; transition: transform 0.5s ease;">
        <img src="Gallery/gnsf.jpg" alt="img1" style="width: 50%; margin-right: 5px; border-radius: 10px;">
        <img src="Gallery/gnsfAGM.jpeg" alt="img2" style="width: 50%; border-radius: 10px;">
        <!-- Add more images below -->
        <img src="Gallery/gnsfAdmission2.jpg" alt="img3" style="width: 50%; border-radius: 10px;">
        <img src="Gallery/gnsfIftar1.jpg" alt="img4" style="width: 50%; border-radius: 10px;">
        <img src="Gallery/gnsfIftar2.jpg" alt="img5" style="width: 50%; border-radius: 10px;">
      </div>
      <a href="javascript:void(0)" onclick="slide(-1)" style="position: absolute; top: 50%; left: 10px; transform: translateY(-50%); text-decoration: none; font-size: 24px;">&#10094;</a>
      <a href="javascript:void(0)" onclick="slide(1)" style="position: absolute; top: 50%; right: 10px; transform: translateY(-50%); text-decoration: none; font-size: 24px;">&#10095;</a>
    </div>
  </div>
</div>

<script>
  let currentIndex = 0;
  const images = document.querySelectorAll('#carousel img');
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
