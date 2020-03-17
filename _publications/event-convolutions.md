---
title: "Asynchronous Spatial Image Convolutions for Event Cameras"
author: "<u>C. Scheerlinck</u>, N. Barnes, R. Mahony"
collection: publications
redirect_from:
  - /2018_event_convolutions
permalink: /event-convolutions
excerpt: 
date: 2019-04-01
venue: IEEE Robotics and Automation Letters, and ICRA (RAL + ICRA; accept. rate 44%)
paperurl: https://doi.org/10.1109/LRA.2019.2893427
citation: 
youtubeId: 
header:
   teaser: gradient_corner_thumbnail.png
---

<a href="https://cedric-scheerlinck.github.io/files/2018_event_convolutions.pdf" target="_blank"><b>PDF</b></a>&emsp;
<a href="https://drive.google.com/drive/folders/1Jv73p1-Hi56HXyal4SHQbzs2zywISOvc" target="_blank"><b>Dataset</b></a>&emsp;
<a href="https://drive.google.com/open?id=10L-t_YACZFb8Vk5cDQa-KWTlnhoItQJt" target="_blank"><b>Slides</b></a>&emsp;
<a href="https://cedric-scheerlinck.github.io/files/2019_ral_convolutions.txt" target="_blank"><b>BibTex</b></a>

![Kernel_pic](/images/kernel1.png){:class="img-responsive"}

<b>Abstract.</b> Spatial convolution is arguably the most fundamental of 2D image processing operations.
Conventional spatial image convolution can only be applied to a conventional image, that is, an array of pixel values (or similar image representation) that are associated with a single instant in time.
Event cameras have serial, asynchronous output with no natural notion of an image frame, and each event arrives with a different timestamp.
In this paper, we propose a method to compute the convolution of a linear spatial kernel with the output of an event camera.
The approach operates on the event stream output of the camera directly without synthesising pseudo-image frames as is common in the literature.
The key idea is the introduction of an internal state that directly encodes the convolved image information, which is updated asynchronously as each event arrives from the camera.
The state can be read-off as-often-as and whenever required for use in higher level vision algorithms for real-time robotic systems.
We demonstrate the application of our method to corner detection, providing an implementation of a Harris corner-response "state" that can be used in real-time for feature detection and tracking on robotic systems.

<br />

**DOI:** <a href="https://doi.org/10.1109/LRA.2019.2893427" target="_blank">10.1109/LRA.2019.2893427</a>

<b>Reference:</b>
* C. Scheerlinck, N. Barnes, R. Mahony, "Asynchronous Spatial Image Convolutions for Event Cameras", IEEE Robotics and Automation Letters, 4(2), April 2019, pp. 816-822.
