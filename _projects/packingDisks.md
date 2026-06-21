---
title: Visualization of Disk Packing and Force Chains
description: A simulaton of packing disks on a hemispherical surface
image: assets/projectPhotos/700grains.png
imagealt: 700 disks packed on a hemispherical surface
showcase: 5
---

**Tools/Skills:** *Python*

The *Tammes problem* refers to the question of how to place points on a spherical surface to maximize the distance between the points. This inspired the question of the optimal packing of circles on the spherical surface for every possible amount of circles. This has been solved for a small number of circles (n < 14), but becomes increasinly complex for larger spherical surfaces.

While trying to understand how spherical grains would pack on a hemispherical surface as a part of my Elastogranular Shells work, it became helpful to visualize this effect. The addition of vacancy defects in the granular arrangement added another layer of complexity. In both cases, finding contact between neighboring disks could inform the presence of force chains, which are networks of grains that distribute the applied forces on a structrue. I created a visualization in Python to study this effect.

[Github: jnarendran/diskPacking](URL "https://github.com/jnarendran/diskPacking")

<div style="line-height:0;">
  <img src="/assets/projectPhotos/700grains.png" width="49%" style="display:inline-block; margin-bottom:3px; margin-top:3px;" />
  <img src="/assets/projectPhotos/600grains6mmDefect.png" width="49%" style="display:inline-block; margin-bottom:3px; margin-top:3px;" />
</div>
<p align="middle">
  There are 700 disks packed on a hemispehrical surface in the left image and 600 disks packed on a hemispherical surface with a 6 mm radius defect at the apex in the right image.
</p>
