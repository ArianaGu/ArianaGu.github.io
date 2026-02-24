---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p class="intro-text">
Hello! I am a graduate student at UC Berkeley, working with Prof. <a href="http://www.laurawaller.com/">Laura Waller</a>. I started my graduate studies in 2022 after graduating with a B.S. in Electrical Engineering from Peking University, China.
</p>

<p class="intro-text">
My research focuses on developing and applying advanced computational imaging techniques, with expertise in signal processing, optimization algorithms, and their applications in image reconstruction and aberration characterization. Previously, I worked on non-line-of-sight imaging with Prof. <a href="https://biostat.wisc.edu/~compoptics/">Andreas Velten</a>. I play with signal processing in the Fourier domain a lot, and I always love combining physical hardware and computational methods to create something new.
</p>

<h2 class="section-heading">Projects</h2>

<div class="project-card">
<h3>Enhanced EUV Mask Imaging using Fourier Ptychographic Microscopy</h3>
<div class="project-authors"><strong>Chaoying Gu</strong>, Antoine Islegen-Wojdyla, Markus Benk, Kenneth A. Goldberg, Laura Waller</div>

<div class="project-venue">
<em>IEEE CISA</em> 2024 &nbsp;·&nbsp; <em>SPIE Advanced Lithography</em> 2025
</div>

<div class="project-links">
<a href="https://ieeexplore.ieee.org/abstract/document/10576262">CISA paper</a>
<a href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13424/134240S/Enhanced-EUV-mask-imaging-using-Fourier-ptychographic-microscopy/10.1117/12.3051223.full">SPIE paper</a>
<a href="https://github.com/ArianaGu/EUV_FPM">code</a>
</div>

<div class="project-highlight">
<ul>
<li>Extensively evaluated reconstruction quality of existing algorithms under EUV microscope aberration and achieved a <strong>36-fold increase</strong> in the usable field-of-view from the nominal 5×5 μm² 
diffraction-limited area.</li>
<li>Developed an <strong>automatic differentiation</strong> framework for system <strong>self-calibration</strong> and wavefront error correction, enabling robust reconstruction of elliptical pupils and attenuated phase shift masks.</li>
<li>Validated Fourier FPM as a promising technique for advanced EUV mask imaging, achieving quantitative phase recovery and through-focus simulation using experimental data from the SHARP EUV microscope at Lawrence Berkeley National Laboratory.</li>

</ul>
</div>

<div class="project-media">
<img src="{{ '/images/autograd.png' | relative_url }}" alt="Fourier ptychography for EUV microscope" />
</div>
</div>

<div class="project-card">
<h3>Large-scale Compressive Microscopy via Diffractive Multiplexing across a Sensor Array</h3>
<div class="project-authors">Kevin C. Zhou, <strong>Chaoying Gu</strong>, Muneki Ikeda, Tina M. Hayward, Nicholas Antipa, Rajesh Menon, Roarke Horstmeyer, Saul Kato, Laura Waller</div>

<div class="project-venue">
<em>Photonics West</em> 2024
</div>

<div class="project-links">
<a href="https://arxiv.org/abs/2507.14437v1">arXiv</a>
<a href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/PC12857/PC128570A/High-throughput-computational-microscopy-with-diffractive-multiplexing-across-a-gigapixel/10.1117/12.3000876.full">abstract</a>
</div>

<div class="project-highlight">
<ul>
<li>Developed a computational microscope using a sensor array and a diffractive optical element (DOE) to achieve high-throughput imaging, covering a <strong>5 cm × 6.6 cm region with ~0.6 gigapixels</strong>.</li>
<li>Developed the patch-based memory-efficient reconstruction algorithm involving deconvolution of diffraction patterns to fill in sensor gaps.</li>
</ul>
</div>

<div class="project-media">
<img src="{{ '/images/mcam_setup.png' | relative_url }}" alt="Large-scale compressive microscopy setup" />
</div>

<div class="project-media">
<video controls playsinline>
  <source src="/files/darkfield_recon_zoom_web.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
</div>
</div>

<div class="project-card">
<h3>Fast Non-line-of-sight Imaging with Non-planar Relay Surfaces</h3>
<div class="project-authors"><strong>Chaoying Gu</strong>, Talha Sultan, Khadijeh Masumnia-Bisheh, Laura Waller, and Andreas Velten</div>

<div class="project-venue">
<em>ICCP</em> 2023
</div>

<div class="project-links">
<a href="https://ieeexplore.ieee.org/abstract/document/10233262">paper</a>
<a href="https://github.com/ArianaGu/3D-RSD">code</a>
</div>

<div class="project-highlight">
<ul>
<li>Proposed a novel computational method that effectively performs 3D diffraction propagation for arbitrary non-planar surfaces.</li>
<li>Achieved <strong>orders of magnitude better complexity</strong> compared to state-of-the-art algorithms without quality degradation, validated on experimental data.</li>
</ul>
</div>

<div class="project-media">
<img src="{{ '/images/r3.png' | relative_url }}" alt="Fast non-line-of-sight imaging results" />
</div>
</div>

<!-- ## Non-Line-of-Sight (NLOS) Imaging System and Algorithm

*Independent Research, Supervised by Prof. Chuanchuan Yang, Institute of Advanced Optical Communication Systems and Networks, Peking University*        (2021/1-2021/8)

- Mastered the theory of phasor-field virtual wave optics and Rayleigh-Sommerfeld Diffraction (RSD);
- Proposed a criterion to explain the selection of virtual illumination function and corresponding wavelength in phasor-field method;
- Developed a fusing algorithm to improve the phasor-field method which can improve the reconstruction SNR by around 20%.

![](/images/r2.png)

## Holographic Reconfigurable Intelligent Surfaces Antenna Design and Optimization

*Independent Research, Supervised by Prof. Lingyang Song, Institute of Wireless Communication, Peking University*        (2020/6-2021/1)

- Surveyed the theory of massive MIMO, hybrid beamforming and reconfigurable intelligent surface;
- Analyzed the method of designing Reconfigurable Holographic Surface (RHS) by constructing varactor diodes in radiation cells to modulate the amplitude;
- Modeled a communication system with several base stations equipped with RHS, and applied fractional and convex optimization algorithm to suppress undesired side-lobes.

![](/images/r1.png) -->
