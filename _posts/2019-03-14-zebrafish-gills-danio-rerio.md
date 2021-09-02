---
layout: post
title: "Zebrafish gills | Danio rerio"
date: 2019-03-14
categories:
  - visualization
tags:
  - zebrafish
  - danio rerio
  - 3d
  - visualization
  - mevislab
---

![Zebrafish head, with its gills.](/assets/2019/03/14/zebrafish-gills-danio-rerio/control06.abstract.jpg)

For a recent project (hopefully more to follow soon) we needed to visualize the head of a zebrafish *with* its gills inside.
The image above shows a three-dimensional visualization of a tomographic scan of such a head, [critically point dried](https://en.wikipedia.org/wiki/Supercritical_drying).
After drying, the head was scanned on a [SkyScan 1172](https://web.archive.org/web/20180816222756/http://bruker-microct.com/products/1172.htm) with a source voltage of 50 kV, a source current of 167 µA with camera and geometry settings leading to an isotropic voxel size of 1.65 µm, the scan took several hours.

The left part of the head is rendered semi-transparently so that the (manually delineated) gills are nicely visible in red.
The tip-to-tip distance of the gills (shown in red) is approximately 1.9 mm. 

The data set was visualized in [MeVisLab](https://mevislab.de) with the [MeVis Path Tracer feature](https://mevislabdownloads.mevis.de/docs/3.1/MeVisLab/Standard/Documentation/Publish/Overviews/PathTracerOverview.html).
