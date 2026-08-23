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
    border-left: 4px solid #EC8F5E;
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
    font-size: 1.5em;
    color: #1a365d;
    border-bottom: 2px solid #EC8F5E;
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
  You can also find my articles on 
  <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.
</p>

<!-- <h2 id="in-press" class="publication-year-heading">In Press &amp; ArXiv</h2> -->

<h2 id="y2026" class="publication-year-heading">2026</h2>

<h2 id="y2025" class="publication-year-heading">2025</h2>

<!-- pub 22 -->
<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/hwzhou2020/hwzhou2020.github.io/master/_publications/AFP.png" width="150" height="150">
  </div><div class="publication-details">
    <font size="4">
      <a href="https://www.nature.com/articles/s41467-025-67460-7" 
      style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            22. Analytic Fourier ptychotomography for aberration-free and high-resolution volumetric refractive index imaging
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
        Zhenyu Dong*, <span style="color: #213555;"><strong>Haowen Zhou*,</strong></span> Ruizhi Cao*, Oumeng Zhang, Shi Zhao, Panlang Lyu, Reinaldo E Alcalde, Changhuei Yang
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;">Nature Communications</span>
        &nbsp; &nbsp;
      </a>
      <a href="/publications/AFP.txt" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #B5CB99;">(BibTex)</span>
      </a>
      <a href="https://mrdongzhenyu.github.io/AFP-Web/" style="text-decoration: none;">
        &nbsp; &nbsp;  <span style="color: #186F65;">[Project Page]</span>
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
