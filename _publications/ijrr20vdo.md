---
title: "VDO-SLAM: A Visual Dynamic Object-aware SLAM System"
author: "<b>Jun Zhang\*</b>, Mina Henein\*, Robert Mahony and Viorela Ila."
collection: publications
permalink: /ijrr20vdo
excerpt: 
date: 2020-11-01
venue: The International Journal of Robotics Research (under review)
paperurl: https://arxiv.org/abs/2005.11052
citation: 
youtubeId: 
header:
   teaser: ijrr20vdo_tn.jpg
---

<a href="https://arxiv.org/pdf/2005.11052.pdf" target="_blank"><b>[PDF]</b></a>&emsp;
<a href="https://github.com/halajun/VDO_SLAM" target="_blank"><b>[Code]</b></a>&emsp;
<a href="https://drive.google.com/file/d/1PbL4KiJ3sUhxyJSQPZmRP6mgi9dIC0iu/view" target="_blank"><b>[Video]</b></a>&emsp;
<a href="https://halajun.github.io/files/zhang20vdoslam.txt" target="_blank"><b>[BibTex]</b></a>

![firenet_banner](/images/banners/ijrr20vdo.png){:class="img-responsive"}

<b>Abstract.</b> 
The scene rigidity assumption, also known as the static world assumption, is common in SLAM algorithms. Most
existing algorithms operating in complex dynamic environments simplify the problem by removing moving objects from
consideration or tracking them separately. Such strong assumptions limit the deployment of autonomous mobile robotic
systems in a wide range of important real world applications involving highly dynamic and unstructured environments.
This paper presents VDO-SLAM, a robust object-aware dynamic SLAM system that exploits semantic information to
enable motion estimation of rigid objects in the scene without any prior knowledge of the objects shape or motion
models. The proposed approach integrates dynamic and static structures in the environment into a unified estimation
framework resulting in accurate robot pose and spatio-temporal map estimation. We provide a way to extract velocity
estimates from object pose change of moving objects in the scene providing an important functionality for navigation
in complex dynamic environments. We demonstrate the performance of the proposed system on a number of real
indoor and outdoor datasets. Results show consistent and substantial improvements over state-of-the-art algorithms.
An open-source version of the source code is available.


<b>Reference:</b>
* J. Zhang\*, M. Henein\*, R. Mahony and V. Ila, "Robust Ego and Object 6-DoF Motion Estimation and Tracking," arXiv:2005.11052, 2020.
