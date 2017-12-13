---
layout: post
title: "3D-print a tomographic scan of a spider"
date: 2017-12-13
categories:
	- 3dprint
	- gift
tags:
	- imagej
	- fiji
	- imageprocessing
	- formlabs
	- 3dprint
---

We obtained a [3D data set of a spider]({{ site.baseurl }}{% post_url 2017-11-15-friendly-neighborhood-spiderman %}) and wanted to make a gift for an [arachnophobic](http://enwp.org/arachnophobia) friend.
Since we have access to a [Form 2 3D printer](https://formlabs.com/3d-printers/form-2/) we wanted to make a 3D print of the data set.

To do so, we did the following steps:
- The size of the dataset was reduced by binning it 2-fold with [Fiji](http://fiji.sc) (e.g. half the image size in each of the x, y and z directions).
- We binarized the dataset to extract the spider from the background, smoothed the binarized image and binarized again to get rid of small noise present in the image.
  After this, we had a 141 MB big tif stack with the size of 612x612x395 pixels.
- By using the [3D Objects Counter](https://imagej.net/3D_Objects_Counter) (also in Fiji) we extracted the biggest object in the dataset, which corresponds to only the spider, discarding noise objects still present in the data set.
- We then viewed the data set as *surface* in the [3D Viewer](https://imagej.net/3D_Viewer) of Fiji, which gave us the result shown in the first picture below.
- The 3D Viewer of Fiji can then be used to save the thresholded spider as [STL file](https://en.wikipedia.org/wiki/STL_(file_format)) ready for printing with a 3D printer (*File* > *Export surfaces* > *STL (binary)*).
  This gave us a 74 MB big STL file (which is quite huge compared to the [other STL files we usually print](https://github.com/habi/OpenSCAD/tree/master/STL)).
- This STL file was then printed in 3D giving the result shown in the second image below.

![3D Viewer](/assets/2017/12/13/3dprint-a-spider/3dviewer.png)
![Final result](/assets/2017/12/13/3dprint-a-spider/printed.jpg)
