---
layout: page
title: Projects
permalink: /projects/
---


<h2>STRUCTURAL DESIGN OF TUNNEL’S PERMANENT LINING</h2>

<div class="justify-text">
As a part of the structural design team at Behan Sadd Co., I was involved in the modeling and design of the permanent lining structures in several projects. Using commercial Finite Element Analysis (FEA) softwares such as SAP2000, PLAXIS 2D, and Ansys Static Structural, I designed the Reinforced Concrete (RC) lining structure that complied with the requirements of EM 1110-2-290, EM 1110-2-2104, and ACI 318-08 standards. 
</div>

### 2D Frame FEA-Based Design Approach

<div class="justify-text">
In this approach, in each of the rock formations along the tunnel axis, we analysed the structural response of the RC lining through a plane-strain FEA procedure. In this method, estimated rock and hydrostatic loads are imposed on the lining as surface loads and the effect of seismic events as asigned deformations [1,2]. The interaction of the lining and the rock is also modeled as a set of non-linear external springs (acting only in pressure). The result is then checked in terms of axial, shear and bending strength.
</div>

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
      <img src="/images/tunnel/shear_tunnel.jpg" alt="moment">
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

### Continuum FEA Modeling of Rock–Concrete Interaction

<div class="justify-text">
This is another method for designing the RC section. The plane-strain idealization is analogously assumed in this approach but we developed a larger mesh that modeled both the media and the structure.
</div>

<figure style="text-align:center;">
  <img src="{{ site.baseurl }}/images/tunnel/continum_model.png" alt="continum" style="width:100%; max-width:1500px;">
  <figcaption>Final displacement contour</figcaption>
</figure>

<div class="justify-text">
The distribution of stresses and strains on the section is then considered as the basis for determining the sufficient strength of the lining structure.
</div>

<div class="swiper mySwiper">
  <div class="swiper-wrapper">

  <div class="swiper-slide">
      <img src="/images/tunnel/axial_plaxis.png" alt="model">
      <div class="slide-caption">
        Axial load diagram of the tunnel section ($ton$)
      </div>
    </div>

  <div class="swiper-slide">
      <img src="/images/tunnel/bending_plaxis.png" alt="hydro">
      <div class="slide-caption">
        Bending moment diagram of the tunnel section ($ton.m$)
      </div>
    </div>

  <div class="swiper-slide">
      <img src="/images/tunnel/shear_plaxis.png" alt="rock_v">
      <div class="slide-caption">
        Shear force diagram of the tunnel section ($ton$)
      </div>
    </div>

  </div>
  
  <!-- Navigation -->
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>

  <!-- Pagination dots -->
  <div class="swiper-pagination"></div>
</div>

---

<h2>STRUCTURAL DESIGN OF RESIDENTIAL BUILDINGS - CONCRETE AND STEEL</h2>

<div class="justify-text">
As part of my final BSc project, I carried out the structural design of a multi-storey residential building using both reinforced concrete and structural steel systems. The project involved the complete analysis and design of key structural elements, including slabs, beams, columns, foundations, and lateral load-resisting systems.
</div>

<div class="justify-text">
Starting from the architectural drawings, I developed the structural system and performed detailed modelling using ETABS for global analysis and SAFE for slab and foundation design. The finite element results were independently verified through analytical and classical structural methods, including Navier’s and Timoshenko’s solutions for slab behavior, as well as the Portal Frame Method and the Equivalent Frame Method for frame analysis.
</div>

<figure style="text-align:center;">
  <img src="{{ site.baseurl }}/images/BSc_Prject.jpg" style="width:100%; max-width:2000px; margin-bottom:10px;">
  <figcaption>Technical Drawings and</figcaption>
</figure>

<div class="justify-text">
All structural elements were designed using the Load and Resistance Factor Design (LRFD) approach. Steel members were checked in accordance with AISC 360 and AISC 341 provisions, while reinforced concrete elements — including foundations — were designed following ACI 318 requirements. Seismic response and lateral performance were explicitly considered throughout the design process.
</div>

<h2>REFERENCES</h2>

[1] Hashash, Y. M., Hook, J. J., Schmidt, B., & Yao, J. I. C. (2001). Seismic design and analysis of underground structures. Tunnelling and underground space technology, 16(4), 247-293.

[2] Schleiss, A. J. (2020). Design of concrete linings of pressure tunnels and shafts for external water pressure. In Tunnelling Asia'97 (pp. 147-156). CRC Press.








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
