---
title: "Mapping"
permalink: /map/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
---

How build a 3D map? Simple, Panther use a stereo camera and sensors to localize itself on the space and detecting and recording.

To make this map, I used:
* ROS melodic
* [RTABmap](http://introlab.github.io/rtabmap/)
* [Meshlab](https://www.meshlab.net/)

# 3D map

In this page a full example of Panther making a 3D map. The output is filtered

<div class="sketchfab-embed-wrapper"> <iframe title="Garden - Panther" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="640" height="480" src="https://sketchfab.com/models/2b4c989204f24723b41ae095925fbb19/embed?autospin=0&autostart=1&preload=1&ui_theme=dark"> </iframe> </div>
{: .full}

## How the map is made

{% include video id="dfKiFW3SGEs" provider="youtube" %}
