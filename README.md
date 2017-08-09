# Seam Erasure
Erases texture seams to prevent visible seams or tearing in displacement maps.

## Overview

Seams of a textures often produce errors when bi-linearly interpolated. This
results in a visible seam line or other undesired artifacts. The goal of this
project is to devise a numerical solution to this problem by minimizing the
energy/error between edge pairs.

This repository contains a JavaScript version of
[seam-erasure](http://github.com/zfergus/seam-erasure-dev). This repository is
built around numeric.js in order to provide a client-side web service.

<img src = "static/img/teaser.png" width="100%">

## Usage

Navigate to the webpage for this repository at
[zfergus.github.io/seam-erasure-js](http://zfergus.github.io/seam-erasure-js).

## Files

* `index.html` - Index page for the webservice.
* `js/` - JavaScript files for Seam-Erasure
* `static/` - Static web page content including style sheets

## Results

### Diffuse Textures

| Before | After |
|:------:|:-----:|
| <img src="static/img/results/Diffuse-Textures/cow-horn-before.png">    | <img src="static/img/results/Diffuse-Textures/cow-horn-after.png">    |
| <img src="static/img/results/Diffuse-Textures/chimp-hand-before.png">     | <img src="static/img/results/Diffuse-Textures/chimp-hand-after.png">     |
| <img src="static/img/results/Diffuse-Textures/nefertiti-before.png">    | <img src="static/img/results/Diffuse-Textures/nefertiti-after.png">    |
| <img src="static/img/results/Diffuse-Textures/teapot-red-before.png">    | <img src="static/img/results/Diffuse-Textures/teapot-red-after-global.png">    |

### Normal Maps

| Before | After |
|:------:|:-----:|
| <img src="static/img/results/Normal-Map-Results/cow/cow-horn-nm-before.png"> | <img src="static/img/results/Normal-Map-Results/cow/cow-horn-nm-after.png"> |
| <img src="static/img/results/Normal-Map-Results/cow/neck-before.png">  | <img src="static/img/results/Normal-Map-Results/cow/neck-after.png">  |
| <img src="static/img/results/Normal-Map-Results/lemon/lemon-before.png">  | <img src="static/img/results/Normal-Map-Results/lemon/lemon-after.png">  |
| <img src="static/img/results/Environment-Map/lemon-tilt-desert-before2.png">  | <img src="static/img/results/Environment-Map/lemon-tilt-desert-after2.png">  |

### Ambient Occlusion

| Before | After |
|:------:|:-----:|
| <img src="static/img/results/Ambient-Occlusion/hercules-before.png"> | <img src="static/img/results/Ambient-Occlusion/hercules-after.png"> |

### Geometry Images

| Before | After |
|:------:|:-----:|
| <img src="static/img/results/Geometry-Images/lemon-before.png"> | <img src="static/img/results/Geometry-Images/lemon-after.png"> |
| <img src="static/img/results/Geometry-Images/lemon-side-before.png">  | <img src="static/img/results/Geometry-Images/lemon-side-after.png">  |
