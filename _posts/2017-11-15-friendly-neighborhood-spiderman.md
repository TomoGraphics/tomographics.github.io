---
layout: post
title: "Friendly Neighborhood Spider-Man | Araneae"
date: 2017-11-15
categories: visualization
tags:
  - spider
  - 3d slicer
  - visualization
  - fun
---

![Spider](/assets/2017/11/15/friendly-neighborhood-spiderman/Spider.png)

This friendly spider was bothering our secretary.
After a nice long bath in 70% Ethanol (scented with Iodine) it was scanned on our [SkyScan 1272](https://www.bruker.com/products/microtomography/micro-ct-for-sample-scanning/skyscan-1272/overview.html) with a source voltage of 50 kV, a source current of 200 µA with camera and geometry settings leading to an isotropic voxel size of 21.7 µm.
The *body* of the spider is approximately 1.2 cm long.

The visualization was made in [3D Slicer](http://slicer.org).
To simulate a shadow, we added a [MIP](https://en.wikipedia.org/wiki/Maximum_intensity_projection)-image (inverted, binarized and heavily blurred) of the spider to the visualization in addition to the 3D stack.
