---
title: "IMACS"
excerpt: "A framework for performance evaluation of image-based control systems<br/>"
collection: tools
youtubeIda: TOB6sSKPfu4
youtubeIdb: 1_JLuMY09-A
youtubeIdc: yJhavfYidko
---
IMACS is a framework for performance evaluation of IMage Approximation in a Closed-loop System.

<p align="center">
  <img src='/images/IMACS.JPG' width="600">
</p>

## Installation

### IMACS SiL with ISP pipeline, C++, and V-REP for LKAS
IMACS software-in-the-loop (SiL) simulator using C++ and V-REP for a vision-based lateral control example can be downloaded from [here](https://github.com/sayandipde/approx_ibc). This version of the SiL simulator uses a reversible pipeline (see [1] for more details).

### IMACS SiL with C++ and V-REP for LKAS
A light-weight SiL simulator using C++ and V-REP to validate your image processing and control algorithms can be downloaded from [here](https://github.com/sajid-mohamed/cppVrepLKAS). This version of the SiL simulator does not have the reversible pipeline.

## Videos

A video for the software-in-the-loop (SiL) simulator of IMACS using C++ and V-REP for a vision-based lateral control example:
{% include youtubePlayer.html id=page.youtubeIda %}

A video for the hardware-in-the-loop (HiL) simulator of IMACS using V-REP and NVIDIA AGX Xavier for a vision-based lateral control example can be found [here](https://youtu.be/1_JLuMY09-A).
{% include youtubePlayer.html id=page.youtubeIdb %}

A video for the hardware-in-the-loop (HiL) simulator of IMACS using Webots and NVIDIA Drive PX2 for a vision-based lateral control example can be found [here](https://youtu.be/yJhavfYidko).
{% include youtubePlayer.html id=page.youtubeIdc %}

## Relevant Publications

[1] S. De, S. Mohamed, K. Bimpisidis, D. Goswami, T. Basten, and H. Corporaal, "Approximation trade offs in an image-based control system," in: Design, Automation and Test in Europe (DATE), 2020.

[2] S. Mohamed, S. De, K. Bimpisidis, V, Nathan, D. Goswami, H. Corporaal, and T. Basten,  "IMACS: A Framework for Performance Evaluation of Image Approximation in a Closed-loop System," in Proceedings of the 8th Mediterranean Conference on Embedded Computing (MECO),  2019. (*Best paper award*) [[pdf]](https://pure.tue.nl/ws/portalfiles/portal/131905081/IMACS.pdf)

The controllers for the LKAS are designed based on the concepts described in the following papers:

[3] S. Mohamed, A. U. Awan, D. Goswami, and T. Basten, "Designing image-based control systems considering workload variations," in: CDC, 2019.

[4] S. Mohamed, D. Zhu, D. Goswami, and T. Basten, "Optimising quality-of-control for data-intensive multiprocessor image-based control systems considering workload variations," in: DSD, 2018.

## Developers

Sajid Mohamed <br/>
Sayandip De <br/>
Konstantinos Bimpisidis <br/>
Vishak Nathan <br/>
Diqing Zhu

## Contact
[s.mohamed@tue.nl](mailto:s.mohamed@tue.nl)
