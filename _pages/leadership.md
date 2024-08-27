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
  <div style="border: 2px solid #e1e4e8; border-radius: 10px; padding: 20px; max-width: 100%; height: 500px; margin: auto; box-shadow: 0px 4px 8px rgba(0,0,0,0.2); background-color: #fff;">
    <div style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="Gallery/gnsfLogo.jpg" alt="GNSF Logo" style="width: 600px; height: auto; margin-right: 20px;">
      <div>
        <h3 style="margin: 0; font-size: 2em;">Vice President</h3>
        <p style="margin: 5px 0; font-size: 1.2em;">Greater Noakhali Students Forum, CUET</p>
        <p style="margin: 0; color: #6a737d; font-size: 1.1em;">Jun 2023 - Present | 1 yr 3 mos</p>
      </div>
    </div>

    <div style="position: relative; width: 100%; height: 300px; overflow: hidden; border-radius: 10px;">
      <div id="carousel" style="display: flex; transition: transform 0.5s ease;">
        <div style="width: 100%; flex-shrink: 0; position: relative; text-align: center;">
          <img src="Gallery/gnsf.png" alt="img1" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
          <div style="position: absolute; bottom: 0; background: rgba(0, 0, 0, 0.5); color: #fff; width: 100%; text-align: center; padding: 10px;">Caption for img1</div>
        </div>
        <div style="width: 100%; flex-shrink: 0; position: relative; text-align: center;">
          <img src="Gallery/gnsfAGM.jpeg" alt="img2" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
          <div style="position: absolute; bottom: 0; background: rgba(0, 0, 0, 0.5); color: #fff; width: 100%; text-align: center; padding: 10px;">Caption for img2</div>
        </div>
        <!-- Add more images below -->
        <div style="width: 100%; flex-shrink: 0; position: relative; text-align: center;">
          <img src="Gallery/gnsfAdmission2.JPG" alt="img3" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
          <div style="position: absolute; bottom: 0; background: rgba(0, 0, 0, 0.5); color: #fff; width: 100%; text-align: center; padding: 10px;">Caption for img3</div>
        </div>
        <div style="width: 100%; flex-shrink: 0; position: relative; text-align: center;">
          <img src="Gallery/gnsfIftar1.jpg" alt="img4" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
          <div style="position: absolute; bottom: 0; background: rgba(0, 0, 0, 0.5); color: #fff; width: 100%; text-align: center; padding: 10px;">Caption for img4</div>
        </div>
        <div style="width: 100%; flex-shrink: 0; position: relative; text-align: center;">
          <img src="Gallery/gnsfIftar2.jpg" alt="img5" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
          <div style="position: absolute; bottom: 0; background: rgba(0, 0, 0, 0.5); color: #fff; width: 100%; text-align: center; padding: 10px;">Caption for img5</div>
        </div>
      </div>
      <a href="javascript:void(0)" onclick="slide(-1)" style="position: absolute; top: 50%; left: 10px; transform: translateY(-50%); text-decoration: none; font-size: 24px; color: #fff; background-color: rgba(0,0,0,0.5); padding: 10px; border-radius: 50%;">&#10094;</a>
      <a href="javascript:void(0)" onclick="slide(1)" style="position: absolute; top: 50%; right: 10px; transform: translateY(-50%); text-decoration: none; font-size: 24px; color: #fff; background-color: rgba(0,0,0,0.5); padding: 10px; border-radius: 50%;">&#10095;</a>
    </div>
  </div>
</div>

<script>
  let currentIndex = 0;
  const images = document.querySelectorAll('#carousel > div');
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

