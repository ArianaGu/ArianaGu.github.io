---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am a new graduate student at UC Berkeley, working with Prof. [Laura Waller](http://www.laurawaller.com/). My research interest lies in computational imaging and optics and I am explorinig diffuser camera & microscope recently. I previously worked on None-line-of-sight imaging with Prof. [Andreas Velten](https://biostat.wisc.edu/~compoptics/). I play with signal processing in the Fourier domain a lot, and I always love combining physical hardware and computational methods to create something.

# Projects

## Towards Full Field-of-View Fourier Ptychography for Extreme Ultraviolet Microscope
**Chaoying Gu**, Antoine Islegen-Wojdyla, Markus Benk, Kenneth A. Goldberg, Laura Waller

*IEEE CISA* 2024 (coming soon)

**Abstract**: We evaluate various Fourier ptychographic microscopy (FPM) reconstruction algorithms using both simulated and experimental data acquired from an Extreme Ultraviolet (EUV, 13.5 nm wavelength) microscope. We specifically focus on the algorithms' ability to robustly address field-dependent aberrations, which enables increased spatial resolution and quantitative phase imaging across an expanded field of view. We systematically compare the algorithms' performance under aberrations for a single zoneplate imaging system, utilizing Fourier Ring Correlation (FRC) as a systematic metric for assessing reconstruction quality. Furthermore, we explore the impact of systematic errors on the reconstruction of experimental data,  aiming to increase the effective field of view by 25-fold, from the nominal 5x5~um$^2$ diffraction-limited area. 

## High-throughput Diffractive Multiplexing Microscopy with Sensor Array
Kevin C Zhou, **Chaoying Gu**, Grace Jiang, Nicholas Antipa, Roarke W Horstmeyer, Laura Waller

*Photonics West* 2024 [[abstract]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/PC12857/PC128570A/High-throughput-computational-microscopy-with-diffractive-multiplexing-across-a-gigapixel/10.1117/12.3000876.full)

**Abstract**: We present a high-resolution, wide-field of view (FOV) computational microscope that employs an array of image sensors with gaps between them and a diffractive optical element (DOE) in the Fourier plane. The sensor array consists of a 6 x 8 array of 13-megapixel sensors (total ~0.6 gigapixels), spanning a 5 cm by 6.6 cm region with a ~22% fill factor. To fill in the inter-sensor gaps without scanning, we introduce a DOE at the pupil that generates a distributed PSF, allowing us to multiplex information from the missing ~78% of the total area into the sensing regions. Our large-scale reconstruction algorithm demixes the superimposed information, resulting in a >4x expanded FOV. Our approach can enable multi-gigapixel imaging in a single snapshot.

I mainly worked on developing the patch-based memory-efficient reconstruction algorithm for demultiplexing.

## Fast Non-line-of-sight Imaging with Non-planar Relay Surfaces

**Chaoying Gu**, Talha Sultan, Khadijeh Masumnia-Bisheh, Laura Waller, and Andreas Velten

*ICCP* 2023  [[paper]](https://ieeexplore.ieee.org/abstract/document/10233262) [[code]](https://github.com/ArianaGu/3D-RSD)

**Abstract**: Non-line-of-sight imaging methods reconstruct images from light captured off a relay surface. In most prior work this relay surface is a diffuse plane. It has been shown that even small deviations from a planar relay wall geometry quickly degrade reconstruction quality. Although existing methods can account for relay surface geometry in a straightforward way, they typically have high computational complexity and take orders of magnitude longer time to compute than state-of-the-art planar methods. In this work, we propose a fast algorithm that can perform non-line-of-sight reconstruction on arbitrary non-planar relay surfaces. Our algorithm has
the same computational and memory complexity as the fastest existing algorithms, yet it achieves comparable reconstruction quality to
the widely-used slower algorithms.

![](/images/r3.png)

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
