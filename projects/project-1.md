---
layout: project
type: project
image: images/gapfilling_square.png
title: Satellite imagery gapfilling
permalink: projects/gapfilling
# All dates must be YYYY-MM-DD format!
date: 2021-10-01
labels:
  - Remote sensing
  - Machine learning
  - Python
summary: We have implemented and tested opensource software toolbox for remote sensing data gapfilling
---

<center><img class="ui image" src="{{ site.baseurl }}/images/gapfilling.png"></center><br>

During my work at Hydrological Institute I proposed a hypothesis about posibility to reconstruct gaps (e.g. clouds) in remote sensing imagery by establishing relationships between pixels based on archived data and machine learning techniques.

We have implemented opensource [software toolbox](https://github.com/Dreamlone/SSGP-toolbox) and test it for different datasets: LST, Albedo, NDVI. Optimistic results were obtained, and I used this algorithm when creating a continuous series of various parameters of the Earth’s surface

You can learn more in the [published article](https://mdpi.com/2072-4292/12/23/3865).