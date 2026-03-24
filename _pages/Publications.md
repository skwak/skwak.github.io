---
layout: page
title: Publications
permalink: /publications/
hide_title: true
---

## ORCID

<div style="text-align: center;">
<a href="https://orcid.org/0000-0001-7693-8992" target="_blank" rel="noopener noreferrer">0000-0001-7693-8992</a>
</div>

---

## Dissertation

<div style="text-align: center; color:#000000">
<a href="../papers/000000289434_20250801133251.pdf" style="color:#000000; font-weight: bold;">
Various numerical schemes and analysis for the conservative Allen–Cahn equation</a>. (2024)
</div>

---

## SCIE / SSCI

<ol class="publication-list" reversed>
  {% assign fixed_pubs = site.data.publications | where_exp: "pub", "pub.published == nil or pub.published == ''" %}
  {% for pub in fixed_pubs %}
    {% include publication.html pub=pub %}
  {% endfor %}
  {% assign pubs = site.data.publications | where_exp: "pub", "pub.published != nil and pub.published != ''" | sort: "published" | reverse %}
  {% for pub in pubs %}
    {% include publication.html pub=pub %}
  {% endfor %}
</ol>

---

### ESCI / SCOPUS

<ol class="publication-list" reversed>
  {% assign pubs = site.data.publications2 | sort: "year" | reverse %}
  {% for pub in pubs %}
    {% include publication.html pub=pub %}
  {% endfor %}
</ol>

---

## Under review / Submitted papers

- <span style="color:#808080; font-weight: bold;">Reconstruction of convexity-preserving local volatility functions</span>. Sangkwon Kim, Jian Wang, **Soobin Kwak**, Hyundong Kim, Yunjae Nam, Junseok Kim.

- <span style="color:#808080; font-weight: bold;">A space-adaptive, unconditionally stable, and maximum bound preserving scheme for the 3D Allen–Cahn equation</span>. **Soobin Kwak**, Junseok Kim.

- <span style="color:#808080; font-weight: bold;">Optimal calibration of the temporally varying volatility function</span>. Jian Wang, Youngjin Hwang, Hyundong Kim, **Soobin Kwak**, Junseok Kim.

- <span style="color:#808080; font-weight: bold;">Numerical investigation of reverse equity-linked securities</span>. Yunjae Nam, Jian Wang, Hyundong Kim, **Soobin Kwak**, Minjoon Bang, Zhengang Li, Junseok Kim.

- <span style="color:#808080; font-weight: bold;">An efficient finite volume lattice Boltzmann method on nonuniform triangular meshes for curved surfaces</span>. Youngjin Hwang, **Soobin Kwak**, Seokjun Ham, Junseok Kim.

- <span style="color:#808080; font-weight: bold;">A time-fractional diffusion model with normalization and short memory effect</span>. Junxiang Yang, Seokjun Ham, **Soobin Kwak**, Yunjae Nam, Zhengang Li, Xinpei Wu, Juho Ma, Junseok Kim.

- <span style="color:#808080; font-weight: bold;">Modified Allen–Cahn equation for curvature-dependent tissue growth on three-dimensional surfaces</span>. **Soobin Kwak**, Yunjae Nam, Juho Ma, and Junseok Kim.

- <span style="color:#808080; font-weight: bold;"> Isotropic discretization of a mathematical model for dendritic growth without artificial curvature</span>. Seokjun Ham, **Soobin Kwak**, Xinpei Wu, Junseok Kim.

- <span style="color:#808080; font-weight: bold;">Practical volume merging method for triply periodic minimal structures</span>. Seungyoon Kang, Yibao Li, **Soobin Kwak**, Yongho Choi, Junseok Kim.

- <span style="color:#808080; font-weight: bold;">A multigrid solver for the  Allen–Cahn equation on a virtual cubic surface</span>. Junxiang Yang, **Soobin Kwak**, Seokjun Ham, Youngjin Hwang, Hyundong Kim, Junseok Kim.

<div style="text-align: right; font-size: 0.9em; color: gray;">
Last updated: {{ site.time | date: "%Y-%m-%d" }}
</div>