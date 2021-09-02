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
- Jupyter
- bioRxiv

---
![Zebrafish head with gills](/assets/2019/08/26/adaptation-of-zebrafish-gills-to-endurance-training/head-without-gills0185.png)

As mentioned [before]({{ site.baseurl }}{% post_url 2019-03-14-zebrafish-gills-danio-rerio %}), we've been working with a bunch of Zebrafishes lately.
For a project on the adaptation of zebrafish gills to endurance training we have been performing a part of the tomographic imaging (the details are specified in the liked post above) as well as the in-depth analysis of the data.

The result of the whole project has recently been accepted as a peer-reviewed manuscript at [PLOS ONE](https://journals.plos.org/plosone/). You can find the published version [here at doi:10.1371/journal.pone.0228333](https://doi.org/10.1371/journal.pone.0228333). Earlier, we submitted a non-peer-reviewed version to [bioRxiv](https://www.biorxiv.org/) which can be found here at [doi:10.1101/744300](http://doi.org/10.1101/744300=).

A quick rundown on how we got to the results:

* One group of fishes was trained in a swim tunnel, they trained relatively to an Olympic athlete, a control group was lazily swimming in a turned-off swim tunnel.
* After training (or non-training), the fishes were sacrificed and prepared for tomographic imaging by our expert lab technicians.
* Oleksiy, Fluri and me scanned the fishes on our old and trusty SkyScan 1172.
* Dea and Matthias delineated the gills in the tomographic datasets, which was the basis for our analysis (the delineated regions are made available by [the OSF](https://osf.io/a5esx/)).
* In a [Jupyter](https://jupyter.org/) we ingested _all_ the data, scattered over the delineated tomographic datasets and several XLS files from the collaborators (the Jupyter notebook is available on GitHub [here](https://github.com/habi/zebra-fish-gills)).
* Based on the measured data we were (among other things) able to show that the gills of trained zebrafish appear significantly more sparse (p=0.0088) than the control group.
  In our opinion, this means that the water can penetrate the gills and pass the gills much more easily in the trained fishes, e.g. they can 'breathe' more easily after a certain training period.
* All the other results, including oxygen consumption and mitoses on the tips of the gills are in themselves also interesting, but have not been performed by me.

Should you be interested in taking a look at how we got to the results, you find the complete analysis (in a Jupyter notebook) and a link to the tomographic datasets of the delineated gills [here at GitHub](https://github.com/habi/zebra-fish-gills).