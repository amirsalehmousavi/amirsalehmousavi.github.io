---
layout: page
title: Projects
permalink: /projects/
---

To be completed.

<div class="swiper mySwiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="/images/tunnel/model.jpg" alt="model">
    </div>
    <div class="swiper-slide">
      <img src="/images/tunnel/hydro_tunnel.jpg" alt="hydro">
    </div>
    <div class="swiper-slide">
      <img src="/images/tunnel/rockload_v.jpg" alt="rock_v">
    </div>
    <div class="swiper-slide">
      <img src="/images/tunnel/rockload_h.jpg" alt="rock_h">
    </div>
    <div class="swiper-slide">
      <img src="/images/tunnel/axial_force.jpg" alt="axial">
    </div>
    <div class="swiper-slide">
      <img src="/images/tunnel/moment_tunnel.jpg" alt="moment">
    </div>
    <div class="swiper-slide">
      <img src="/images/tunnel/seismic_tunnel_design.jpg" alt="seismic">
    </div>
  </div>

  <!-- Navigation -->
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>

  <!-- Pagination dots -->
  <div class="swiper-pagination"></div>
</div>






<script>
  const swiper = new Swiper('.mySwiper', {
    loop: true,
    autoplay: {
      delay: 4000,
      disableOnInteraction: false,
    },
    pagination: {
      el: '.swiper-pagination',
      clickable: true,
    },
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
  });
</script>
