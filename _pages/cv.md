---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- <embed src="../files/CV_Priyanka.pdf" type="application/pdf" /> -->

Education
=========
* Ph.D. in Computer Science and Engineering, Indian Institute of Technology Indore (Jul. 2022 - present)
* M.Tech. in Computer Science, Devi Ahilya Vishwavidyalaya, Indore, (Jul. 2017- Jun. 2019)
* B.E. in Computer Science and Engineering, Jawaharlal Institute of Technology, Khargone (Jul. 2013 - Jun. 2017)


Projects
=========
* Automate the Traffic Sign Detection and Recognition (TSRD) in Varying Lighting Conditions
  * Implemented an adaptive framework for real-world traffic scenarios, integrating a Fuzzy Inference System (FIS), an enhancement module, and an object detection network.
  * The FIS dynamically decides if an image needs enhancement. The enhancement module enhances the brightness of the image while preserving color details. Finally, YOLOv8 is employed for TSRD.

* Traffic Sign Detection and Recognitions (TSDR) in Low-Quality Images
  * Implemented a two-step method for TSDR, where signs are often hard to recognize due to poor visibility, blurriness, and bad lighting conditions.
  * First, images are enhanced using a modified MIRNet model. Second, the YOLOv4 model recognizes the signs from the improved images.

* Real-Time Hand Gesture Recognition using CNN
  * Real-time hand gesture recognition model captures webcam images and classifies the detected gestures in real time.
  * The training utilized a dataset of American sign language alphabets, spanning from A to Z.
  * Additionally, an accuracy comparison was carried out between training from scratch and applying transfer learning on the VGG16 model. 


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work Experience 
=============== 

* Devi Ahilya Vishwavidyalaya, Indore  (Jan. 2020 - May 2020)
  * I have taught Computer Architecture and Data Mining.
  * Curated course and conducted lab sessions.

