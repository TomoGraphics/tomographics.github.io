---
layout: post
title: Lecture on (micro)tomography
date: 2019-12-20
categories:
- teaching
tags:
- visualization
- teaching
- latex
- github
- students
- mic

---
![mouse skull](/assets/2019/12/20/lecture-on-microtomography/mouse_skull.gif)

Today, I gave a lecture on (micro)tomography, in front of a bunch of students from the University of Bern, as part of the [Lecture Series on Advanced Microscopy](https://www.mic.unibe.ch/lecture.php).
I tried to show them what can be nicely done with - for example - our [desktop micro-CT scanners](https://bruker.com/skyscan1272).
The whole presentation was crafted in LaTeX and is [available on GitHub](https://github.com/habi/lecture.microtomography), should you be interested in it.
The student handout of the presentation was automatically compiled and put online using a [GitHub Action](https://github.com/features/actions) ([this one here](https://github.com/xu-cheng/latex-action)), you can download a copy of the [handout here](https://habi.github.io/Lecture.Microtomography/XRayMicroTomography.Handout.pdf) if you like.

The poster image of this blog post shows a three-dimensional visualization of a mouse skull which is approximately 25 mm long from the nose to the back of the skull.
The mouse head was scanned on a [SkyScan 1172](https://web.archive.org/web/20180816222756/http://bruker-microct.com/products/1172.htm) with a source voltage of 59 kV, a source current of 167 µA with camera and geometry settings leading to an isotropic voxel size of 7.96 µm.
The whole scan took about 74 minutes.
I used the data set throughout the lecture to show different details and intricacies of the tomographic imaging process.

The skull was visualized in [MeVisLab](http://www.sci.utah.edu/software/imagevis3d.html) with the [MeVis Path Tracer feature](https://mevislabdownloads.mevis.de/docs/3.1/MeVisLab/Standard/Documentation/Publish/Overviews/PathTracerOverview.html).
The movie was generated from a set of single frames [in the same manner as described previously]({{ site.baseurl }}{% post_url 2017-11-14-rat-eye %}).