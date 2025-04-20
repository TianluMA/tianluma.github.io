---
title: "Research"
layout: single
permalink: /research/
author_profile: true
---



## Research Overview

<div align="justify">
My research focuses on advancing the fundamental theory and practical implementation of Wireless Power Transfer (WPT) systems. This includes system modeling, control strategies, coupler design, efficiency optimization, and biomedical applications. The overview below presents a comprehensive visual summary of these key research directions and their interconnections.
</div>

<div class="carousel-container overview-carousel">
  <div class="carousel-slide overview-slide">
    <img src="/images/research/Overview/Tianlu Ma_Overview_20250311_01.jpg" alt="Research Overview 1">
    <img src="/images/research/Overview/Tianlu Ma_Overview_20250311_02.jpg" alt="Research Overview 2">
    <img src="/images/research/Overview/Tianlu Ma_Overview_20250311_03.jpg" alt="Research Overview 3">
  </div>
  <button class="prev" onclick="moveOverviewSlide(-1)">&#10094;</button>
  <button class="next" onclick="moveOverviewSlide(1)">&#10095;</button>
</div>

<p style="text-align:right; font-size: 0.9em; color: gray; margin-top: 0.5em;">
© Tianlu Ma. All rights reserved. Please do not reproduce without permission.
</p>

<style>
.overview-carousel {
  position: relative;
  max-width: 90%;
  margin: 1.5em auto;
  overflow: hidden;
  border: 1px solid #ddd;
  border-radius: 8px;
}
.overview-slide {
  display: flex;
  transition: transform 0.4s ease-in-out;
}
.overview-slide img {
  min-width: 100%;
  height: auto;
  display: block;
}
.overview-carousel .prev,
.overview-carousel .next {
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
.overview-carousel .prev { left: 10px; }
.overview-carousel .next { right: 10px; }
</style>

<script>
let currentOverviewIndex = 0;
const overviewSlides = document.querySelectorAll('.overview-slide img');
function showOverviewSlide(index) {
  const container = document.querySelector('.overview-slide');
  const total = overviewSlides.length;
  currentOverviewIndex = (index + total) % total;
  container.style.transform = `translateX(-${currentOverviewIndex * 100}%)`;
}
function moveOverviewSlide(n) {
  showOverviewSlide(currentOverviewIndex + n);
}
window.addEventListener('DOMContentLoaded', () => {
  showOverviewSlide(currentOverviewIndex);
});
</script>



## 1. Unified Full-load Discrete-time Model

<div align="justify">
The unified full-load discrete-time (UFDT) model is capable of precisely describing the characteristics of WPT systems under both light and heavy load conditions. It seamlessly incorporates the dual-mode behavior of the secondary-side rectifier operating in continuous conduction mode (CCM) and discontinuous conduction mode (DCM), providing a comprehensive analytical framework for full-range power transfer dynamics.
</div>

<div class="carousel-container ufdt-carousel">
  <div class="carousel-slide ufdt-slide">
    <img src="/images/research/UFDT_Model/Tianlu Ma_UFDT_20250311_01.jpg" alt="UFDT Slide 1">
    <img src="/images/research/UFDT_Model/Tianlu Ma_UFDT_20250311_02.jpg" alt="UFDT Slide 2">
    <img src="/images/research/UFDT_Model/Tianlu Ma_UFDT_20250311_03.jpg" alt="UFDT Slide 3">
    <img src="/images/research/UFDT_Model/Tianlu Ma_UFDT_20250311_04.jpg" alt="UFDT Slide 4">
    <img src="/images/research/UFDT_Model/Tianlu Ma_UFDT_20250311_05.jpg" alt="UFDT Slide 5">
    <img src="/images/research/UFDT_Model/Tianlu Ma_UFDT_20250311_06.jpg" alt="UFDT Slide 6">
    <img src="/images/research/UFDT_Model/Tianlu Ma_UFDT_20250311_07.jpg" alt="UFDT Slide 7">
  </div>
  <button class="prev" onclick="moveUFDTSlide(-1)">&#10094;</button>
  <button class="next" onclick="moveUFDTSlide(1)">&#10095;</button>
</div>

<p style="text-align:right; font-size: 0.9em; color: gray; margin-top: 0.5em;">
© Tianlu Ma. All rights reserved. Please do not reproduce without permission.
</p>

<style>
.ufdt-carousel {
  position: relative;
  max-width: 90%;
  margin: 1.5em auto;
  overflow: hidden;
  border: 1px solid #ddd;
  border-radius: 8px;
}
.ufdt-slide {
  display: flex;
  transition: transform 0.4s ease-in-out;
}
.ufdt-slide img {
  min-width: 100%;
  height: auto;
  display: block;
}
.ufdt-carousel .prev,
.ufdt-carousel .next {
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
.ufdt-carousel .prev { left: 10px; }
.ufdt-carousel .next { right: 10px; }
</style>

<script>
let currentUFDTIndex = 0;
const ufdtSlides = document.querySelectorAll('.ufdt-slide img');
function showUFDTSlide(index) {
  const container = document.querySelector('.ufdt-slide');
  const total = ufdtSlides.length;
  currentUFDTIndex = (index + total) % total;
  container.style.transform = `translateX(-${currentUFDTIndex * 100}%)`;
}
function moveUFDTSlide(n) {
  showUFDTSlide(currentUFDTIndex + n);
}
window.addEventListener('DOMContentLoaded', () => {
  showUFDTSlide(currentUFDTIndex);
});
</script>




## 2. Periodic Energy Control

<div align="justify">
The Periodic Energy Control (PEC) strategy controls the output of the WPT system by regulating the energy injected into the resonant network during each switching cycle. It features fast dynamic response and strong immunity to mutual inductance variation. Moreover, PEC enables full-load Zero Voltage Switching (ZVS), making it a promising solution for efficient and robust WPT operation. However, special attention must be given to the system startup process, which requires separate design to ensure stability and reliability.
</div>

<div class="carousel-container pec-carousel">
  <div class="carousel-slide pec-slide">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_01.jpg" alt="PEC Slide 1">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_02.jpg" alt="PEC Slide 2">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_03.jpg" alt="PEC Slide 3">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_04.jpg" alt="PEC Slide 4">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_05.jpg" alt="PEC Slide 5">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_06.jpg" alt="PEC Slide 6">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_07.jpg" alt="PEC Slide 7">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_08.jpg" alt="PEC Slide 8">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_09.jpg" alt="PEC Slide 9">
    <img src="/images/research/PEC/Tianlu Ma_PEC_20250311_10.jpg" alt="PEC Slide 10">
  </div>
  <button class="prev" onclick="movePECSlide(-1)">&#10094;</button>
  <button class="next" onclick="movePECSlide(1)">&#10095;</button>
</div>

<p style="text-align:right; font-size: 0.9em; color: gray; margin-top: 0.5em;">
© Tianlu Ma. All rights reserved. Please do not reproduce without permission.
</p>

<style>
.pec-carousel {
  position: relative;
  max-width: 90%;
  margin: 1.5em auto;
  overflow: hidden;
  border: 1px solid #ddd;
  border-radius: 8px;
}

.pec-slide {
  display: flex;
  transition: transform 0.4s ease-in-out;
}

.pec-slide img {
  min-width: 100%;
  height: auto;
  display: block;
}

.pec-carousel .prev, .pec-carousel .next {
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

.pec-carousel .prev { left: 10px; }
.pec-carousel .next { right: 10px; }
</style>

<script>
let currentPECIndex = 0;
const pecSlides = document.querySelectorAll('.pec-slide img');

function showPECSlide(index) {
  const slideContainer = document.querySelector('.pec-slide');
  const totalSlides = pecSlides.length;
  if (index >= totalSlides) currentPECIndex = 0;
  else if (index < 0) currentPECIndex = totalSlides - 1;
  else currentPECIndex = index;

  slideContainer.style.transform = `translateX(-${currentPECIndex * 100}%)`;
}

function movePECSlide(n) {
  showPECSlide(currentPECIndex + n);
}

window.addEventListener('DOMContentLoaded', () => {
  showPECSlide(currentPECIndex);
});
</script>


## 3. Model Predictive Control for Dynamic Wireless Power Transfer

<div align="justify">
This research proposes a model predictive control (MPC) strategy for dynamic wireless power transfer (DWPT) systems, which enables accurate and responsive power regulation under continuously changing coupling conditions. The controller predicts future system behaviors and optimizes the control actions in real time, ensuring high efficiency, stable power delivery, and robustness to misalignment and movement. It also supports multi-segment coordination and plug-and-play operations.
</div>

<div class="carousel-container dwpt-carousel">
  <div class="carousel-slide dwpt-slide">
    <img src="/images/research/DWPT_MPC/Tianlu Ma_DWPT_MPC_20250311_01.jpg" alt="DWPT MPC Slide 1">
    <img src="/images/research/DWPT_MPC/Tianlu Ma_DWPT_MPC_20250311_02.jpg" alt="DWPT MPC Slide 2">
    <img src="/images/research/DWPT_MPC/Tianlu Ma_DWPT_MPC_20250311_03.jpg" alt="DWPT MPC Slide 3">
    <img src="/images/research/DWPT_MPC/Tianlu Ma_DWPT_MPC_20250311_04.jpg" alt="DWPT MPC Slide 4">
    <img src="/images/research/DWPT_MPC/Tianlu Ma_DWPT_MPC_20250311_05.jpg" alt="DWPT MPC Slide 5">
    <img src="/images/research/DWPT_MPC/Tianlu Ma_DWPT_MPC_20250311_06.jpg" alt="DWPT MPC Slide 6">
  </div>
  <button class="prev" onclick="moveDWPTSlide(-1)">&#10094;</button>
  <button class="next" onclick="moveDWPTSlide(1)">&#10095;</button>
</div>

<p style="text-align:right; font-size: 0.9em; color: gray; margin-top: 0.5em;">
© Tianlu Ma. All rights reserved. Please do not reproduce without permission.
</p>

<style>
.dwpt-carousel {
  position: relative;
  max-width: 90%;
  margin: 1.5em auto;
  overflow: hidden;
  border: 1px solid #ddd;
  border-radius: 8px;
}

.dwpt-slide {
  display: flex;
  transition: transform 0.4s ease-in-out;
}

.dwpt-slide img {
  min-width: 100%;
  height: auto;
  display: block;
}

.dwpt-carousel .prev, .dwpt-carousel .next {
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

.dwpt-carousel .prev { left: 10px; }
.dwpt-carousel .next { right: 10px; }
</style>

<script>
let currentDWPTIndex = 0;
const dwptSlides = document.querySelectorAll('.dwpt-slide img');

function showDWPTSlide(index) {
  const slideContainer = document.querySelector('.dwpt-slide');
  const totalSlides = dwptSlides.length;
  if (index >= totalSlides) currentDWPTIndex = 0;
  else if (index < 0) currentDWPTIndex = totalSlides - 1;
  else currentDWPTIndex = index;

  slideContainer.style.transform = `translateX(-${currentDWPTIndex * 100}%)`;
}

function moveDWPTSlide(n) {
  showDWPTSlide(currentDWPTIndex + n);
}

window.addEventListener('DOMContentLoaded', () => {
  showDWPTSlide(currentDWPTIndex);
});
</script>


## 4. MHz Wireless Power Transfer for Biomedical Applications

<div align="justify">
This research focuses on MHz-level wireless power transfer (WPT) systems tailored for implantable biomedical devices. By leveraging compact coils, high-frequency operation, and tissue-safe power regulation strategies, these systems support wireless lighting, stimulation, and sensing in untethered microscale platforms such as micro-LEDs. The solution emphasizes miniaturization, efficient coupling through biological tissue, and biocompatible packaging.
</div>

<div class="carousel-container bio-carousel">
  <div class="carousel-slide bio-slide">
    <img src="/images/research/Biomedical/Tianlu Ma_uLEDs_20250311_01.jpg" alt="uLED Slide 1">
    <img src="/images/research/Biomedical/Tianlu Ma_uLEDs_20250311_02.jpg" alt="uLED Slide 2">
    <img src="/images/research/Biomedical/Tianlu Ma_uLEDs_20250311_03.jpg" alt="uLED Slide 3">
    <img src="/images/research/Biomedical/Tianlu Ma_uLEDs_20250311_04.jpg" alt="uLED Slide 4">
  </div>
  <button class="prev" onclick="moveBioSlide(-1)">&#10094;</button>
  <button class="next" onclick="moveBioSlide(1)">&#10095;</button>
</div>

<p style="text-align:right; font-size: 0.9em; color: gray; margin-top: 0.5em;">
© Tianlu Ma. All rights reserved. Please do not reproduce without permission.
</p>

<style>
.bio-carousel {
  position: relative;
  max-width: 90%;
  margin: 1.5em auto;
  overflow: hidden;
  border: 1px solid #ddd;
  border-radius: 8px;
}

.bio-slide {
  display: flex;
  transition: transform 0.4s ease-in-out;
}

.bio-slide img {
  min-width: 100%;
  height: auto;
  display: block;
}

.bio-carousel .prev, .bio-carousel .next {
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

.bio-carousel .prev { left: 10px; }
.bio-carousel .next { right: 10px; }
</style>

<script>
let currentBioIndex = 0;
const bioSlides = document.querySelectorAll('.bio-slide img');

function showBioSlide(index) {
  const slideContainer = document.querySelector('.bio-slide');
  const totalSlides = bioSlides.length;
  if (index >= totalSlides) currentBioIndex = 0;
  else if (index < 0) currentBioIndex = totalSlides - 1;
  else currentBioIndex = index;

  slideContainer.style.transform = `translateX(-${currentBioIndex * 100}%)`;
}

function moveBioSlide(n) {
  showBioSlide(currentBioIndex + n);
}

window.addEventListener('DOMContentLoaded', () => {
  showBioSlide(currentBioIndex);
});
</script>

## Outlook and Future Work

<div align="justify">
Our future research will focus on enhancing wireless power transfer technologies in the following key directions:
</div>

- Dynamic Wireless Power Transfer 
- MHz WPT in Biomedical Application
- AI Technology in WPT

