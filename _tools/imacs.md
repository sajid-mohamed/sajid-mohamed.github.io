---
title: "IMACS"
excerpt: "A framework for performance evaluation of image-based control systems<br/>"
collection: tools
youtubeIda: TOB6sSKPfu4
youtubeIdb: 1_JLuMY09-A
youtubeIdc: yJhavfYidko
---
IMACS is a framework for performance evaluation of IMAge in the Closed-loop System.

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

## Publications

[1] S. De, Y. Huang, S. Mohamed, D. Goswami, and H. Corporaal, &quot;Hardware- and Situation-Aware Sensing for Robust
Closed-Loop Control Systems,&quot; <i>In Design, Automation and Test in Europe Conference (DATE)</i>, 2021. <a href="https://sajid-mohamed.github.io/files/DATE2021paper.pdf">[paper]</a>

[2] S. De, S. Mohamed, D. Goswami, and H. Corporaal,  &quot;Approximation-Aware Design of an Image-Based Control System,&quot; <i>In IEEE Access</i>, 2020.  <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9189775">[pdf]</a> <a href="http://sajid-mohamed.github.io/files/bib_de2020access.txt">[bibtex]</a>

[3] S. De, S. Mohamed, K. Bimpisidis, D. Goswami, T. Basten, and H. Corporaal, &quot;Approximation trade offs in an image-based control system,&quot; <i>In Design, Automation and Test in Europe Conference (DATE)</i>, 2020. <a href="https://sajid-mohamed.github.io/files/DATE2020paper.pdf">[paper]</a> <a href="https://sajid-mohamed.github.io/files/DATE2020slides.pdf">[slides]</a> <a href="http://sajid-mohamed.github.io/files/bib_de2020approximation.txt">[bibtex]</a>

[4] S. Mohamed, S. De, K. Bimpisidis, V, Nathan, D. Goswami, H. Corporaal, and T. Basten,  &quot;IMACS: a framework for performance evaluation of image approximation in a closed-loop system,&quot; <i>In 8th Mediterranean Conference on Embedded Computing (MECO)</i>, 2019. <a href="https://pure.tue.nl/ws/portalfiles/portal/131905081/IMACS.pdf">[pdf]</a> <a href="https://sajid-mohamed.github.io/files/IMACS_.pptx">[slides]</a> <a href="https://sajid-mohamed.github.io/tools/imacs/">[details]</a> <a href="http://sajid-mohamed.github.io/files/bib_mohamed2019imacs.txt">[bibtex]</a> (*Best paper award*) 

The controllers for the LKAS are designed based on the concepts described in the following papers:

[5] S. Mohamed, D. Goswami, V. Nathan, R. Rajappa, and T. Basten, &quot;A scenario-and platform-aware design flow for image-based control systems,&quot; <i>In Microprocessors and Microsystems (MICPRO)</i>, 2020. <a href="https://doi.org/10.1016/j.micpro.2020.103037">[DOI]</a> <a href="https://sajid-mohamed.github.io/files/103037preprint.pdf">[pdf]</a> <a href="http://sajid-mohamed.github.io/files/bib_mohamed2020scenario.txt">[bibtex]</a>

[6] S. Mohamed, A. U. Awan, D. Goswami, and T. Basten, &quot;Designing image-based control systems considering workload variations,&quot; <i>In IEEE 58th Conference on Decision and Control (CDC)</i>, 2019. <a href="https://pure.tue.nl/ws/portalfiles/portal/144403064/CDC_cam_ready.pdf">[pdf]</a> <a href="https://sajid-mohamed.github.io/files/CDC19SMohamed.pptx">[slides]</a> <a href="http://sajid-mohamed.github.io/files/bib_mohamed2019designing.txt">[bibtex]</a>

[7] S. Mohamed, D. Zhu, D. Goswami, and T. Basten, &quot;Optimising Quality-of-Control for Data-intensive Multiprocessor Image-Based Control Systems considering Workload Variations,&quot; <i>In Digital System Design (DSD)</i>, 2018. <a href="https://pure.tue.nl/ws/portalfiles/portal/145692692/PID5432947.pdf">[pdf]</a> <a href="https://sajid-mohamed.github.io/files/SPADe_DSD2018v2.pptx">[slides]</a> <a href="http://sajid-mohamed.github.io/files/bib_mohamed2018optimising.txt">[bibtex]</a>

## Developers

Sajid Mohamed <br/>
Sayandip De <br/>
Konstantinos Bimpisidis <br/>
Vishak Nathan <br/>
Diqing Zhu <br/>
Yingkai Huang <br/>
Chaolun Ma

## Contact
[s.mohamed@tue.nl](mailto:s.mohamed@tue.nl)
[Dip Goswami, Assistant Professor, Eindhoven University of Technology](mailto:d.goswami@tue.nl)
