---
title: "Activities"
layout: single
permalink: /activities/
author_profile: true
---


## Recent Activities

### 2025.09.24 – 09.26: Participation in PCIM Asia 2025 (Shanghai, China)

<div align="justify">
From 24 to 26 September 2025, I participated in PCIM Asia 2025, held in Shanghai, China.  
This international conference and exhibition brought together experts and researchers in power electronics and intelligent motion.  
It was an excellent opportunity to exchange ideas on emerging technologies such as high-frequency converters and wireless power transfer systems.
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; max-width: 90%; margin: 1.5em auto;">
  <img src="/images/activities/2025 PCIM/PCIM1.jpg" alt="PCIM Asia 2025 - Photo 1" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
  <img src="/images/activities/2025 PCIM/PCIM2.jpg" alt="PCIM Asia 2025 - Photo 2" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
</div>



### 2025.06.16: CityUHK Department of Electrical Engineering Commencement Ceremony

<div align="justify">
On 16 June 2025, I attended the Commencement Ceremony of the Department of Electrical Engineering, City University of Hong Kong, as the <b>Graduate Representative</b> for the Class of 2025.  
It was a memorable occasion celebrating the academic achievements of our graduates. I was honored to deliver a speech on behalf of the graduating class.
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; max-width: 90%; margin: 1.5em auto;">
  <img src="/images/activities/2025 Graduation/Graduation1.jpg" alt="CityUHK Commencement 2025 - Photo 1" style="max-height: 300px; width: auto; border-radius: 8px; border: 1px solid #ddd;">
  <img src="/images/activities/2025 Graduation/Graduation2.jpg" alt="CityUHK Commencement 2025 - Photo 2" style="max-height: 300px; width: auto; border-radius: 8px; border: 1px solid #ddd;">
</div>


### 2025.04.25 - 04.27: The 18th Symposium on Power Electronics & Electrical Drives (SPEED 2025)

<div align="justify">
I participated in the 18th Symposium on Power Electronics & Electrical Drives (SPEED 2025), held from 25 to 27 Apr 2025. It was a great opportunity to engage with leading scholars in the field of power electronics and electrical drives.
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; max-width: 90%; margin: 1.5em auto;">
  <img src="/images/activities/2025 SPEED/Speed_1.jpg" alt="SPEED 2025 - Photo 1" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
  <img src="/images/activities/2025 SPEED/Speed_2.jpg" alt="SPEED 2025 - Photo 2" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
  <img src="/images/activities/2025 SPEED/Speed_3.jpg" alt="SPEED 2025 - Photo 3" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
  <img src="/images/activities/2025 SPEED/Speed_4.jpg" alt="SPEED 2025 - Photo 4" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
</div>

### 2024.12.03: Ph.D. Thesis Defense

<div align="justify">
I successfully defended my Ph.D. thesis on 3 Dec 2024 at City University of Hong Kong. This milestone marks the culmination of my doctoral journey.
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; max-width: 90%; margin: 1.5em auto;">
  <img src="/images/activities/2024 Phd Defense/Phd Defense_2.jpg" alt="Ph.D. Defense 2024 - Photo 2" style="max-height: 300px; width: auto; border-radius: 8px; border: 1px solid #ddd;">
  <img src="/images/activities/2024 Phd Defense/Phd Defense_3.jpg" alt="Ph.D. Defense 2024 - Photo 3" style="max-height: 300px; width: auto; border-radius: 8px; border: 1px solid #ddd;">
</div>

### 2024.05.21: Visit from IEEE PELS President Prof. Brad Lehman

<div align="justify">
We had the great honor of welcoming Prof. Brad Lehman, President of IEEE Power Electronics Society (PELS), to visit our laboratory. I had a memorable discussion and took photos with him during the visit.
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; max-width: 90%; margin: 1.5em auto;">
  <img src="/images/activities/2024 Brad Lehman Visit/Brad_Visit_1.jpg" alt="Prof. Brad Lehman Visit 2024 - Photo 1" style="max-height: 300px; width: auto; border-radius: 8px; border: 1px solid #ddd;">
  <img src="/images/activities/2024 Brad Lehman Visit/Brad_Visit_2.jpg" alt="Prof. Brad Lehman Visit 2024 - Photo 2" style="max-height: 300px; width: auto; border-radius: 8px; border: 1px solid #ddd;">
</div>




<p style="text-align:right; font-size: 0.9em; color: gray; margin-top: 0.5em;">
© Tianlu Ma. All rights reserved. Please do not reproduce without permission.
</p>


<style>
.carousel-container {
  position: relative;
  max-width: 90%;
  margin: 1.5em auto;
  overflow: hidden;
  border: 1px solid #ddd;
  border-radius: 8px;
}
.carousel-slide {
  display: flex;
  transition: transform 0.4s ease-in-out;
}
.carousel-slide img {
  min-width: 100%;
  height: auto;
  display: block;
}
.carousel-container .prev,
.carousel-container .next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: rgba(0,0,0,0.5);
  color: white;
  font-size: 1.8em;
  border: none;
  padding: 0.3em 0.6em;
  cursor: pointer;
  z-index: 10;
}
.carousel-container .prev { left: 10px; }
.carousel-container .next { right: 10px; }
</style>

<script>
function createCarouselFunctions(slideClass, slideVar) {
  let currentIndex = 0;
  const slides = document.querySelectorAll('.' + slideClass + ' img');
  window['move' + slideVar + 'Slide'] = function(n) {
    const container = document.querySelector('.' + slideClass);
    const total = slides.length;
    currentIndex = (currentIndex + n + total) % total;
    container.style.transform = `translateX(-${currentIndex * 100}%)`;
  }
  window.addEventListener('DOMContentLoaded', () => {
    window['move' + slideVar + 'Slide'](0);
  });
}
createCarouselFunctions('speed-slide', 'Speed');
createCarouselFunctions('defense-slide', 'Defense');
createCarouselFunctions('sspel-slide', 'SSPEL');
</script>
