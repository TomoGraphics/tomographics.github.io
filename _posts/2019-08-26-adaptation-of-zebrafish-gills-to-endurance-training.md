---
layout: post
title: Adaptation of zebrafish gills to endurance training
date: 2019-08-26
categories:
- manuscripts
tags:
- zebrafish
- gills
- visualization
- jupyter
- biorxiv

---
![Zebrafish head with gills](/assets/2019/08/26/adaptation-of-zebrafish-gills-to-endurance-training/head-without-gills0185.png)

As mentioned [before]({{ site.baseurl }}{% post_url 2019-03-14-zebrafish-gills-danio-rerio %}), we've been working with a buch of zebrafishes lately.
For a project on the adaptation of zebrafish gills to endurance training we have been performing a part of the tomographic imaging (the details are specified in the liked post above) as well as the in-depth analysis of the data.

The result of the whole project has been submitted to [PLOS ONE](). While the manuscript undergoes the review process, you can find a non peer-reviewed preprint of the manuscript here on [bioRxiv](https://www.biorxiv.org/): [http://doi.org/10.1101/744300](http://doi.org/10.1101/744300=).

A quick rundown on how we got to the results:

* One group of fishes was trained in a swim tunnel, they trained relatively to an olympic athlete, a control group was lazily swimming in a turned-off swim tunnel.
* After training (or non-training), the fishes were sacrificed and prepared for tomographic imaging by our expert lab technicians.
* Oleksiy, Fluri and me scanned the fishes on our old and trusty SkyScan 1172.
* Dea and Matthias delinated the gills in the tomographic datasets, which was the basis for our analysis (the delineated regions are made available by [the OSF](https://osf.io/a5esx/)).
* In a [Jupyter](https://jupyter.org/) we ingested _all_ the data, scattered over the delineated tomographic datasets and several XLS files from the collaborators (the Jupyter notebook is available on GitHub [here](https://github.com/habi/zebra-fish-gills)).
* Based on the measured data we were (among other things) able to show that the gills of trained zebrafish appear significantly more sparse (p=0.0088) than the control group.
  In our opinion, this means that the water can penetrate the gills and pass the gills much more easily in the trained fishes, e.g. they can 'breathe' more easily after a certain training period.
* All the other results, including oxygen consumption and mitoses on the tips of the gills are in themselves also interesting, but have not been performed by me.
  I invite the keen reader to read up on all the information in the preprint!