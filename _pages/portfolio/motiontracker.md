---
layout: archive
title: "MotionTracker"
excerpt: "A Python-based target tracking system that worked with both moving targets and cameras for HP SCDS."
permalink: /portfolio/motiontracker/
header:
  image: /images/MotionTracker.png
  teaser: /images/MotionTracker.png
gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"

---

![full](/images/MotionTracker.gif){: full}

This project gathers all the development that has been carried out for a year and a half for the realization of an application capable of tracking a moving object with a camera also in motion. The program has been developed using the Python programming language and the OpenCV library, both the treatment of videos and images and the implementation of the detection algorithms. Since
one of the main objectives of this project was to create a modular application that could be improved in the future or coupled to other systems, the study and the corresponding documentation on the technologies used are also collected, including the one for libraries used and for the motion detection algorithms so that, in the future, we have a clear record of the reasons behind each design decision and of the internal workings of the program. For that purpose, this document includes, in addition to the aforementioned, all the development of the project with a specific explanation of the partial objectives into which the
process was divided for each of the meetings, carried out according to the agile methodology. Finally, further possible improvements or extensions of this application are proposed, such as the implementation of deep learning with some of the investigated libraries or the coupling to a mechanical system to carry out a fully automated target tracking thanks to the current operation of the program’s code.

{% include gallery.html caption="This is a sample gallery to go along with this case study." %}

This project has been carried out in collaboration with HP-SCDS.

https://hpscds.com/xv-observatorio-hp-2020/