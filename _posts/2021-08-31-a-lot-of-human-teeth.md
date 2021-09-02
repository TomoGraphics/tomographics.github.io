---
layout: post
title: "Human tooth | Homo"
date: 2021-08-31
categories:
  - visualization
  - publications
tags:
  - human
  - tooth
  - zmk
  - manubot
  - visualization
  - movie
  - gif
---

![A human tooth](assets/2021/08/31/a-lot-of-human-teeth/Tooth045.gif)

We recently were able to publish a study where we automatically segmented the root canal space in human teeth: https://doi.org/10.1186/s12903-021-01551-x

Here's a little explanation of the study, in which we used the *sample changer* of our [SkyScan 1272](https://www.bruker.com/en/products-and-solutions/microscopes/3d-x-ray-microscopes/skyscan-1272.html) quite intensively.
In collaboration with the [zmk bern – Zahnmedizinische Kliniken](https://www.zmk.unibe.ch/) we were asked to image +100 human teeth (excess material from tooth operations/extractions) and prepare the tomographic datasets for characterization.
As mentioned, we used the sample changer of our scanner for this, on which we mounted each tooth in a [custom-designed and 3D-printed sample holder](https://github.com/TomoGraphics/Hol3Drs/blob/master/STL/tooth_holder3.stl).
After aqcuiring +800 GB of raw data we reconstructed the data into about 35 GB of reconstructions.
All these reconstructions were then ingested into a pipeline in a [Jupyter notebook](https://jupyter.org/) with Python code.
The notebook is freely available here: https://github.com/habi/zmk-tooth-cohort and is able to be run with [`binder`](https://mybinder.org/) by clicking the relevant button in the GitHub repository.

After we've prepared the data for our collaborators we've tried to write up the whole process as a publication.
This was achieved by using the collaborative writing function of [Manuscripts.io](https://manuscripts.io/).
A *ready to submit*-version of the manuscript was exported to a set of Markdown files and imported into a [`manubot`](https://manubot.org/)-enabled [repository on GitHub](https://github.com/habi/zmk-tooth-cohort-method-manuscript), which automatically converts the text into both a nice-looking [website](https://habi.github.io/zmk-tooth-cohort-method-manuscript/) and [PDF filehttps://habi.github.io/zmk-tooth-cohort-method-manuscript/manuscript.pdf).
The publication has just been accepted for PLOS ONE and should show up in relevant search engines, soon.

- Tooth is 2401 slices long with 10 um voxel size

"
The tooth shown in the header image of this post was scanned on a [SkyScan 1272]((https://www.bruker.com/en/products-and-solutions/microscopes/3d-x-ray-microscopes/skyscan-1272.html)) with a source voltage of 80 kV, a source current of 125 µA with camera and geometry settings leading to an isotropic voxel size of 10 µm.
The whole scan took about 3 hours and 15 minutes.
The animation was generated with [MeVisLab](https://www.mevislab.de/) using the [MeVis Path Tracer feature](https://mevislabdownloads.mevis.de/docs/3.1/MeVisLab/Standard/Documentation/Publish/Overviews/PathTracerOverview.html).
The movie was generated from a set of single frames [in the same manner as described previously]({{ site.baseurl }}{% post_url 2017-11-14-rat-eye %}).
