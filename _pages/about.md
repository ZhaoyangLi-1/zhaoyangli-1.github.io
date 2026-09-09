---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
:root {
  --about-page-font-size: 17px;
  --about-page-max-width: 1400px;   /* 想更宽/更窄，改这一个值即可 */
  --sidebar-width: 290px;

  /* ===== 标题字号：改这三个值即可 ===== */
  --section-title-font-size: 22px;  /* About Me / Education / Publications 这类大标题 */
  --sub-title-font-size: 18px;      /* 二级标题 */
  --sub-sub-title-font-size: 14px;  /* 三级标题 */
}


#main {
  max-width: var(--about-page-max-width) !important;
}

@media screen and (min-width: 925px) {
  .sidebar {
    width: calc(var(--sidebar-width) - 1em) !important;
  }

  .sidebar .author__avatar img,
  .sidebar img.author__avatar {
    width: 100% !important;
    max-width: var(--sidebar-width) !important;
    height: auto !important;
    aspect-ratio: 1 / 1;
    object-fit: cover;
  }

  .page {
    width: calc(100% - var(--sidebar-width)) !important;
    padding-right: 0 !important;
  }
}

/* Body text: apply the font-size variable to all non-heading content.
   Headings are deliberately excluded here and sized in the block below. */
.page__content,
.page__content p,
.page__content li,
.page__content dl,
.page__content dt,
.page__content dd,
.page__content ul,
.page__content ol,
.page__content table,
.page__content tr,
.page__content td,
.page__content th,
.page__content a,
.page__content b,
.page__content strong,
.page__content i,
.page__content em,
.page__content span,
.page__content small,
.page__content sup,
.page__content sub,
#pubs,
#pubs td,
#pubs tr,
#pubs table,
#pubs b,
#pubs strong,
#pubs i,
#pubs em,
#pubs a,
#pubs span {
  font-size: var(--about-page-font-size);
}

/* ===== Section headings (About Me / Education / Publications ...) ===== */
.page__content h1,
.page__content h1 a {
  font-size: var(--section-title-font-size);
  line-height: 1.3;
  margin-top: 1.4em;
  margin-bottom: 0.4em;
}

.page__content h2,
.page__content h2 a {
  font-size: var(--sub-title-font-size);
  line-height: 1.35;
  margin-top: 1.2em;
  margin-bottom: 0.4em;
}

.page__content h3,
.page__content h3 a {
  font-size: var(--sub-sub-title-font-size);
  line-height: 1.4;
}

/* Keep superscript markers slightly smaller and raised (normal <sup> behavior) */
.page__content sup,
#pubs sup {
  font-size: calc(var(--about-page-font-size) * 0.75);
  vertical-align: baseline;
  position: relative;
  top: -0.3em;
}

.edu-item {
  display: flex;
  align-items: center;
  gap: 18px;
  margin: 0 0 20px 0;
  border: 0 !important;
  background: transparent !important;
}

.edu-logo {
  flex: 0 0 92px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.edu-logo img {
  max-width: 90px !important;
  max-height: 52px !important;
  width: auto !important;
  height: auto !important;
  object-fit: contain;
  border: 0 !important;
  box-shadow: none !important;
}

.edu-logo img.logo-ucsd {
  max-height: 71px !important;
  max-width: 93px !important;
}

.edu-logo img.logo-wisc {
  max-height: 68px !important;
  max-width: 90px !important;
}

.edu-text {
  line-height: 1.7;
}

.page__content {
  line-height: 1.8;
}

#pubs .card, #pubs .panel, #pubs .list-group-item, #pubs .media,
#pubs .paper-card, #pubs .project-card, #pubs .article-card,
#pubs .archive__item, #pubs .archive__item-teaser {
  border: 0 !important;
  box-shadow: none !important;
  background: transparent !important;
}

#pubs table, #pubs tr, #pubs td {
  border: 0 !important;
  background: transparent !important;
}

#pubs .card, #pubs .panel, #pubs .list-group-item,
#pubs .archive__item {
  padding: 0 0 16px 0;
  margin: 0 0 18px 0;
}

#pubs {
  line-height: 2.0;
}

/* ===== Publication thumbnails: scale with the page width ===== */
#pubs td.pub-media {
  width: 30%;
}

#pubs .pub-media img,
#pubs .pub-media video {
  width: 100%;
  height: auto;
  display: block;
  border: 0 !important;
  box-shadow: none !important;
}

@media screen and (max-width: 600px) {
  #pubs td.pub-media {
    width: 38%;
  }
}
</style>

About Me
======
I am a first-year Ph.D. student in the [Computer Science Department](https://www.cs.rutgers.edu/) at Rutgers University–New Brunswick, advised by [Abdeslam Boularias](https://rl.cs.rutgers.edu/). Before joining Rutgers, I worked closely with [Erdem Biyik](https://ebiyik.github.io/). I received my M.S. in [Electrical and Computer Engineering](https://www.ece.ucsd.edu/) from [UC San Diego](https://www.ucsd.edu/), where I was fortunate to work with [Hao Su](https://www.haosu.ai/) and [Pengtao Xie](https://pengtaoxie.github.io/). Prior to that, I earned a B.S. with a double major in [Computer Science](https://guide.wisc.edu/undergraduate/letters-science/computer-sciences/computer-sciences-bs/) and [Mathematics](https://guide.wisc.edu/undergraduate/letters-science/mathematics/mathematics-ba/mathematics-mathematics-data-science-ba/#text) from [UW–Madison](https://www.wisc.edu/), where I worked with [Vikas Singh](https://www.biostat.wisc.edu/~vsingh/).

Email: [zl1308@rutgers.edu](mailto:zl1308@rutgers.edu)

<!-- <p>
  <img src="images/logos.png"
       alt="UW–Madison · UC San Diego · Rutgers"
       style="width:100%; max-width:500px; height:auto; display:block; margin:16px 0;">
</p>

Educations
======
- **Ph.D. in Computer Science**  
  Rutgers University–New Brunswick | 09/2026 - Present

- **M.S. in Electrical and Computer Engineering (Intelligent Systems, Robotics & Control)**  
  University of California, San Diego | 09/2023 - 06/2025

- **B.S. in Computer Science & Mathematics (Double Major)**  
  University of Wisconsin-Madison | 01/2021 - 05/2023 -->

Education
======

<div class="edu-item">
  <div class="edu-logo"><img src="images/RU.png" alt="Rutgers"></div>
  <div class="edu-text">
    <b>Ph.D. in Computer Science</b><br>
    Rutgers University–New Brunswick | 09/2026 – Present
  </div>
</div>

<div class="edu-item">
  <div class="edu-logo"><img class="logo-ucsd" src="images/UCSD.png" alt="UC San Diego"></div>
  <div class="edu-text">
    <b>M.S. in Electrical and Computer Engineering</b><br>
    Intelligent Systems, Robotics &amp; Control<br>
    University of California, San Diego | 09/2023 – 06/2025
  </div>
</div>

<div class="edu-item">
  <div class="edu-logo"><img class="logo-wisc" src="images/WISC.png" alt="UW–Madison"></div>
  <div class="edu-text">
    <b>B.S. in Computer Science &amp; Mathematics</b> (Double Major)<br>
    University of Wisconsin–Madison | 01/2021 – 05/2023
  </div>
</div>


  

Publications and Preprints
======

\* indicates equal contribution.

<div id="pubs">
<table border="0" width="100%" cellspacing="12" cellpadding="0">
  <!-- BFN Policy-->
  <tr>
    <td class="pub-media" valign="top">
      <video autoplay loop muted playsinline>
        <source src="files/xArm.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td valign="top">
      <b>BFN Policy: Visuomotor Policy Learning for Hybrid Action Spaces via Bayesian Flow Networks</b><br>
      <b>Zhaoyang Li<sup>*</sup></b>, Aleyna Kara<sup>*</sup>, Abha Jha<sup>*</sup>, Bo-Ruei Huang, Majid Khadiv, Erdem Biyik<br>
      <i>Under review.</i>
    </td>
  </tr>
  <!-- ORIC -->
  <tr>
    <td class="pub-media" valign="top">
      <img src="images/ORIC.png" alt="ORIC" loading="lazy">
    </td>
    <td valign="top">
      <b>ORIC: Benchmarking Object Recognition in Incongruous Context for Large Vision-Language Models.</b><br>
      <b>Zhaoyang Li<sup>*</sup></b>, Zhan Ling<sup>*</sup>, Yuchen Zhou, Litian Gong, Erdem Biyik, Hao Su.<br>
      <i>IEEE / CVF Computer Vision and Pattern Recognition Conference <b>(CVPR)</b> 2026.</i><br>
      <a href="https://arxiv.org/abs/2509.15695v5">Paper</a> |
      <a href="https://github.com/ZhaoyangLi-1/ORIC">Code</a>
    </td>
  </tr>
  <!-- S2V-Dagger -->
  <tr>
    <td class="pub-media" valign="top">
      <img src="images/s2v_dagger.png" alt="S2V-Dagger" loading="lazy">
    </td>
    <td valign="top">
      <b>When Should We Prefer State-to-Visual DAgger Over Visual Reinforcement Learning?</b><br>
      Tongzhou Mu<sup>*</sup>, <b>Zhaoyang Li<sup>*</sup></b>, Stanislaw Wiktor Strzelecki<sup>*</sup>, Xiu Yuan, Yunchao Yao, Litian Liang, Aditya Gulati, Hao Su.<br>
      <i>AAAI Conference on Artificial Intelligence <b>(AAAI)</b> 2025.</i><br>
      <a href="https://arxiv.org/abs/2412.13662">Paper</a> |
      <a href="https://github.com/ZhaoyangLi-1/s2v-dagger">Code</a>
    </td>
  </tr>
</table>
</div>


Professional Service
======

- Reviewer, AAAI 2025 Workshop on Large Language Models and Generative AI for Health  
- Reviewer, AAAI

Teaching
======

Teaching Assistant at UW-Madison - Spring 2023  
- CS540: Introduction to Artificial Intelligence  

Peer Mentor at UW-Madison - Fall 2022  
- CS537: Introduction to Operating System
