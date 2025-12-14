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
      <div class="slide-caption">
        Finite element model of the tunnel lining
      </div>
    </div>

  <div class="swiper-slide">
      <img src="/images/tunnel/hydro_tunnel.jpg" alt="hydro">
      <div class="slide-caption">
        Hydrostatic pressure distribution on tunnel boundary ($\frac{ton}{m}$)
      </div>
    </div>

  <div class="swiper-slide">
      <img src="/images/tunnel/rockload_v.jpg" alt="rock_v">
      <div class="slide-caption">
        Vertical rock load distribution acting on tunnel crown ($\frac{ton}{m}$)
      </div>
    </div>

  <div class="swiper-slide">
      <img src="/images/tunnel/rockload_h.jpg" alt="rock_h">
      <div class="slide-caption">
        Horizontal rock load distribution acting on tunnel lining ($\frac{ton}{m}$)
      </div>
    </div>

  <div class="swiper-slide">
      <img src="/images/tunnel/axial_force.jpg" alt="axial">
      <div class="slide-caption">
        Axial force distribution along the tunnel lining ($ton$)
      </div>
    </div>

  <div class="swiper-slide">
      <img src="/images/tunnel/moment_tunnel.jpg" alt="moment">
      <div class="slide-caption">
        Bending moment diagram of the tunnel section ($ton.m$)
      </div>
    </div>

  <div class="swiper-slide">
      <img src="/images/tunnel/seismic_tunnel_design.jpg" alt="seismic">
      <div class="slide-caption">
        Seismic loading and tunnel design response (MDE Level)
      </div>
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
