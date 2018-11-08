---
layout: post
title: "Wasp | Vespidae"
date: 2018-07-24
categories:
  - visualization
tags:
  - insect
  - wasp
  - visualization
  - imagevis3d
  -
---

![A wasp](/assets/2018/07/24/wasp-vespidae/wasp.gif)

A wasp died in our living room.
We dried it and scanned it on a [SkyScan 1272](https://www.bruker.com/products/microtomography/micro-ct-for-sample-scanning/skyscan-1272/overview.html) with a source Voltage of 50 kV, a source current of 200 µA with camera and geometry settings leading to an isotropic voxel size of 15 µm, the scan took about 18 minutes.
The hind part of the body has an approximate width of 4 mm, the head is approximately 3 mm wide.

The data set was visualized in [ImageVis3D](http://www.sci.utah.edu/software/imagevis3d.html) and exported to a set of images while the wasp rotates.
The movie shown above was made exactly like the one for the [rat eye]({{ site.baseurl }}{% post_url 2017-11-14-rat-eye %}), namely saved to single images, converted to a movie with `avconv` and to an autoplaying gif file with a script.
