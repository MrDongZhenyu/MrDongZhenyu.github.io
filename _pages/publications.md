---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<style>
  div.pub {
    line-height: 120%;
  }

  .publication {
    display: grid;
    grid-template-columns: 150px 1fr;
    align-items: flex-start;
    gap: 20px;
    margin-bottom: 30px;
    padding: 20px;
    background: #f8f9fa;
    border-radius: 8px;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .publication:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }

  .publication-image {
    width: 150px;
    height: 150px;
    overflow: hidden;
    border-radius: 6px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  }

  .publication-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
    loading: lazy;
  }

  .publication-image img:hover {
    transform: scale(1.05);
  }

  .publication-details {
    flex-grow: 1;
  }

  .back-to-top {
    position: fixed;
    right: 24px;
    bottom: 24px;
    display: inline-flex;
    align-items: center;
    background: #EC8F5E;
    color: #fff;
    padding: 10px 16px;
    border-radius: 999px;
    font-weight: 600;
    text-decoration: none;
    box-shadow: 0 6px 14px rgba(0,0,0,0.15);
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.2s ease, transform 0.2s ease;
    z-index: 10;
  }

  .back-to-top:hover {
    transform: translateY(-2px);
  }

  .back-to-top.show {
    opacity: 1;
    pointer-events: auto;
  }

  .publication-year-heading {
    margin: 50px 0 15px;
    font-size: 1.25em;
    color: #1a365d;
    border-bottom: 2px solid #000000;
    padding-bottom: 6px;
    scroll-margin-top: 90px;
  }

  .publication-index {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin: 25px 0 35px;
  }

  .publication-index a {
    padding: 8px 16px;
    border-radius: 999px;
    border: 1px solid #EC8F5E;
    color: #B2533E;
    font-weight: 600;
    background: #fff5ef;
    transition: background 0.2s ease, color 0.2s ease;
  }

  .publication-index a:hover {
    background: #EC8F5E;
    color: #fff;
  }

  /* Mobile Optimization */
  @media (max-width: 768px) {
    .publication {
      grid-template-columns: 1fr;
      gap: 15px;
      padding: 15px;
    }

    .publication-image {
      width: 100%;
      height: 200px;
      justify-self: center;
    }

    .publication-index {
      flex-direction: column;
    }

    .publication-index a {
      width: 100%;
      text-align: center;
    }

    .back-to-top {
      right: 16px;
      bottom: 16px;
    }
  }
</style>

<div id="pub-top"></div>

<p>
  You can also find my publications on 
  <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.
</p>
<strong>Click titles to access papers.</strong>

<!-- <h2 id="in-press" class="publication-year-heading">In Press &amp; ArXiv</h2> -->

<h2 id="y2026" class="publication-year-heading">2026</h2>

<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/MrDongZhenyu/mrdongzhenyu.github.io/master/_publications/sexing_eggs_paper.png" width="150" height="150">
  </div><div class="publication-details">
    <font size="4">
      <a href="https://doi.org/10.1371/journal.pone.0323847" 
      style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            9. Detection of non-invasive sexing of early chick embryos in intact eggs using laser speckle contrast imaging and deep neural networks
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
         Simon Mahler*, Anika Arora*, Carol Readhead*, Siyuan Yin*, Surya Narayanan Hari, Ellie Wang, Cecilia I. Moxley, Abdullahi A. Adeboye, <span style="color: #213555;"><strong>Zhenyu Dong,</strong></span> Haowen Zhou, Xi Chen, Marianne Bronner, Changhuei Yang
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;">Plos One, 2026</span>
        &nbsp; &nbsp;
      </a>
      <a href="/publications/sexing_eggs_paper.txt" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #B5CB99;">(BibTex)</span>
      </a>  
    </font>
    <br>
    <font size="3">
      <span style="color: gray;">
         We integrated LSCI with deep learning to investigate early-stage sex differentiation of chicken embryos from extraembryonic vascular patterns.
      </span>
    </font>
  </div>
</div>


<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/MrDongZhenyu/mrdongzhenyu.github.io/master/_publications/DAbI.png" width="150" height="150">
  </div><div class="publication-details">
    <font size="4">
      <a href="https://doi.org/10.1038/s41467-026-72287-x" 
      style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            8. Digital defocus aberration interference for automated optical microscopy
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
         Haowen Zhou*, Shi Zhao*, Yujie Fan, <span style="color: #213555;"><strong>Zhenyu Dong,</strong></span> Oumeng Zhang, Viviana Gradinaru, Changhuei Yang
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;">Nature Communications, 2026</span>
        &nbsp; &nbsp;
      </a>
      <a href="/publications/DAbI.txt" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #B5CB99;">(BibTex)</span>
      </a>
      <a href="https://hwzhou2020.github.io/DAbI-Web/" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #186F65;">[Project Page]</span>
      </a>
      <a href="https://github.com/hwzhou2020/DAbI" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #D97706;">[Code Link]</span>
      </a>      
    </font>
    <br>
    <font size="3">
      <span style="color: gray;">
         We recently observed a phenomenon that the digitally summed Fourier spectrum of two images acquired from two-angle illumination exhibits interference-like fringe modulation when the sample is out-of-focus.
         These digital fringes correlate directly with defocus through a physics-based relation. Based on this principle, we developed an automatic, efficient, and generalizable defocus detection method termed digital defocus aberration interference (DAbI).
      </span>
    </font>
  </div>
</div>


<h2 id="y2025" class="publication-year-heading">2025</h2>

<!-- pub 22 -->
<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/MrDongZhenyu/mrdongzhenyu.github.io/master/_publications/AFP.png" width="150" height="150">
  </div><div class="publication-details">
    <font size="4">
      <a href="https://doi.org/10.1038/s41467-025-67460-7" 
      style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            7. Analytic Fourier ptychotomography for aberration-free and high-resolution volumetric refractive index imaging
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
        <span style="color: #213555;"><strong>Zhenyu Dong*,</strong></span>  Haowen Zhou*, Ruizhi Cao*, Oumeng Zhang, Shi Zhao, Panlang Lyu, Reinaldo E Alcalde, Changhuei Yang
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;">Nature Communications, 2025</span>
        &nbsp; &nbsp;
      </a>
      <a href="/publications/AFP.txt" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #B5CB99;">(BibTex)</span>
      </a>
      <a href="https://mrdongzhenyu.github.io/AFP-Web/" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #186F65;">[Project Page]</span>
      </a>
      <a href="https://github.com/MrDongZhenyu/AFP" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #D97706;">[Code Link]</span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: gray;">
         We propose Analytic Fourier Ptychotomography (AFP), a computational microscopy technique that analytically reconstructs aberration-free, complex-valued 3D RI distributions without iterative optimization or axial scanning. 
      </span>
    </font>
  </div>
</div>

<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/MrDongZhenyu/mrdongzhenyu.github.io/master/_publications/MMF-Radon.png" width="150" height="150">
  </div><div class="publication-details">
    <font size="4">
      <a href="https://doi.org/10.1002/lpor.202500089" 
      style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            6. Rotational Memory Effect-Inspired Radon Domain Learning Empowers Image Transmission Through Multimode Fibers
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
        Ninghe Liu, Lele Wang, Zhaofan He, Haoran Zhang, <span style="color: #213555;"><strong>Zhenyu Dong,</strong></span> Dan Li, Ping Yan, Qirong Xiao
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;"> Laser & Photonics Reviews, 2025</span>
        &nbsp; &nbsp;
      </a>
      <a href="/publications/MMF-Radon.txt" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #B5CB99;">(BibTex)</span>
      </a>
      <a href="https://github.com/NeoLiu02/Fiber-Radon" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #D97706;">[Code Link]</span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: gray;">
         We developed RTMnet, a physics-guided cross-domain learning framework integrating the rotational memory effect, Radon transform, and Fourier neural operator for efficient image transmission through MMFs. RTMnet achieves high-fidelity reconstruction with an order-of-magnitude lower computational cost than conventional DNNs and generalizes to arbitrarily rotated images using only non-rotated training data.
      </span>
    </font>
  </div>
</div>

<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/MrDongZhenyu/mrdongzhenyu.github.io/master/_publications/nifedipine_paper.png" width="150" height="150">
  </div><div class="publication-details">
    <font size="4">
      <a href="https://doi.org/10.1016/j.ydbio.2024.12.005" 
      style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            5. Automated non-invasive laser speckle imaging of the chick heart rate and extraembryonic blood vessels and their response to Nifedipine and Amlodipine drugs
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
        Carol Readhead*, Simon Mahler*, <span style="color: #213555;"><strong>Zhenyu Dong,</strong></span> Yuki Sato, Changhuei Yang, Marianne E. Bronner
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;"> Developmental Biology, 2025</span>
        &nbsp; &nbsp;
      </a>
      <a href="/publications/nifedipine_paper.txt" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #B5CB99;">(BibTex)</span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: gray;">
        We built an automated, incubator-integrated LSCI platform for longitudinal monitoring of embryonic heart rate, blood-flow dynamics, and vascular structures. We established its potential as a rapid, quantitative platform for screening cardiovascular drugs and assessing their effects on embryonic heart function.
      </span>
    </font>
  </div>
</div>

<h2 id="y2024" class="publication-year-heading">2024</h2>
<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/MrDongZhenyu/mrdongzhenyu.github.io/master/_publications/Egg_LSCI.png" width="150" height="150">
  </div><div class="publication-details">
    <font size="4">
      <a href="https://doi.org/10.1364/BOE.530366" 
      style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            4. Non-invasive laser speckle contrast imaging (LSCI) of extra-embryonic blood vessels in intact avian eggs at early developmental stages
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
        <span style="color: #213555;"><strong>Zhenyu Dong*,</strong></span> Simon Mahler*, Carol Readhead, Xi Chen, Maya Dickson, Marianne Bronner, and Changhuei Yang
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;"> Biomedical Optics Express, 2024</span>
        &nbsp; &nbsp;
        <span style="color: #186F65;"><strong>Editor's Pick & Journal Cover</strong> </span>
      </a>
      <a href="/publications/Egg_LSCI.txt" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #B5CB99;">(BibTex)</span>
      </a>
      <a href="https://github.com/MrDongZhenyu/Egg-LSCI" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #D97706;">[Code Link]</span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: gray;">
        We built a non-invasive LSCI system for visualizing extra-embryonic blood vessels through intact avian eggs,enabling detection of vessels as small as ∼100 𝜇m in diameter. We improved temporal resolution for real-time and longitudinal monitoring of blood-flow dynamics and embryonic heart rate through intact eggshells. We further extended longitudinal vascular imaging to day 5 by developing a time-domain Fourier high-pass filtering method to suppress low-frequency artifacts from eggshell cracks and embryo body movements. We finally implemented a machine-learning framework with feature extraction to classify embryonic developmental stages from LSCI images, achieving 85% accuracy.
      </span>
    </font>
  </div>
</div>

<h2 id="y2023" class="publication-year-heading">2023</h2>

<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/MrDongZhenyu/mrdongzhenyu.github.io/master/_publications/STABLE.png" width="150" height="150">
  </div><div class="publication-details">
    <font size="4">
      <a href="https://doi.org/10.1038/s41566-023-01240-x" 
      style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            3. Single multimode fibre for in vivo light-field-encoded endoscopic imaging
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
        Zhong Wen, <span style="color: #213555;"><strong>Zhenyu Dong,</strong></span> Qilin Deng, Chenlei Pang, Clemens F. Kaminski, Xiaorong Xu, Huihui Yan, Liqiang Wang, Songguo Liu, Jianbin Tang, Wei Chen, Xu Liu, Qing Yang 
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;"> Nature Photonics, 2023</span>
      </a>
      <a href="/publications/STABLE.txt" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #B5CB99;">(BibTex)</span>
      </a>
      <a href="https://www.opticsjournal.net/CL/ZGGX?type=view&postid=PT231120000060gDjGm" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #D97706;">[Media Coverage]</span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: gray;">
        We developed STABLE, a bend-resistant 3D imaging method that enables MMF imaging under practical fiber deformations. We proposed a single-DMD scheme for simultaneous amplitude, phase, and polarization modulation of the fiber incident wavefront, enabling full-vector transmission-matrix (TM) measurement of long and bent MMFs and precise wavefront control at the fiber output. We implemented reflective guide stars as closed-loop feedback to identify the optimal fiber TM from a compact pre-calibrated TM library, enabling efficient compensation of bending-induced TM variations and stable imaging under fiber deformation. We demonstrated high-resolution in-vivo MMF endoscopic imaging of the gastrointestinal tract in living mice.
      </span>
    </font>
  </div>
</div>

<h2 id="y2022" class="publication-year-heading">2022</h2>

<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/MrDongZhenyu/mrdongzhenyu.github.io/master/_publications/MMFDeblur.png" width="150" height="150">
  </div><div class="publication-details">
    <font size="4">
      <a href="https://doi.org/10.1364/OL.469034" 
      style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            2. Spatially variant deblur and image enhancement in a single multimode fiber imaged by deep learning
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
        Qilin Deng, Zhong Wen, <span style="color: #213555;"><strong>Zhenyu Dong,</strong></span> Jianbin Tang, Wei Chen, Xu Liu, Qing Yang
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;"> Optics Letters, 2022</span>
      </a>
      <a href="/publications/MMFDeblur.txt" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #B5CB99;">(BibTex)</span>
      </a>
      <a href="https://github.com/Kilin617/Space-variant-Deblur-and-Dnoise-in-MMF" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #D97706;">[Code Link]</span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: gray;">
       We implemented a CNN-based framework to deblur and denoise MMF endoscopic images degraded by spatially varying PSFs, achieving 5-ms reconstruction and up to three orders of magnitude speed up over iterative methods.     
      </span>
    </font>
  </div>
</div>

<!-- <font size="2">
  <br>
  <span style="color: gray;">
    Updated on Sept. 14, 2024
  </span>
</font> -->




<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=feZDslgAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %} -->

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

<script>
  (function() {
    var targetId = 'backToTop';
    var existing = document.getElementById(targetId);
    var backToTop = existing;

    if (!backToTop) {
      backToTop = document.createElement('a');
      backToTop.id = targetId;
      backToTop.href = '#pub-top';
      backToTop.className = 'back-to-top';
      backToTop.textContent = '↑ Back to Top';
      document.body.appendChild(backToTop);
    }

    function scrollPosition() {
      return window.pageYOffset || document.documentElement.scrollTop || document.body.scrollTop || 0;
    }

    function toggleBackToTop() {
      if (scrollPosition() > 400) {
        backToTop.classList.add('show');
      } else {
        backToTop.classList.remove('show');
      }
    }

    window.addEventListener('scroll', toggleBackToTop, { passive: true });
    toggleBackToTop();
  })();
</script>
