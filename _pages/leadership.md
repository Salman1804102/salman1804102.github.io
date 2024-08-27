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
      <img src="Gallery/gnsfLogo.jpg" alt="img1" style="width: 600px; height: auto; margin-right: 20px;">
      <div>
        <h3 style="margin: 0; font-size: 2em;">Vice President</h3>
        <p style="margin: 5px 0; font-size: 1.2em;">Greater Noakhali Students Forum, CUET</p>
        <p style="margin: 0; color: #6a737d; font-size: 1.1em;">Jun 2023 - Present | 1 yr 3 mos</p>
      </div>
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

