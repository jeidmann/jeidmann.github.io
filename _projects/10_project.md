---
layout: page
title: Bringing topotoolbox to Python
description: Topotoolbox is an open-source topographic analysis program that only works in MATLAB. I am working with Dr. Sean Gallen to re-code programs into Python3.
img: assets/img/TopoToolbox.png
importance: 2
category: work
---

<div class="float-center">
    <div class="col">
        {% include figure.liquid path="assets/img/TopoToolbox.png"  class="img-fluid rounded z-depth-1" %}
    </div>
</div>

TopoToolbox is a MATLAB-based program that is widely used throughout the academic and Geosciences community. One advantage to TopoToolbox, is that it utilizes MATLAB's ability to work well with matrices. This feature makes it advantageous for work with remote sensing imagery, which works on long/lat and UTM gridded systems, and overlap this imagery with disparate types of other data sets. MATLAB, however, is a proprietary software that is expensive outside of the academic sphere, limiting its use outside of academia.

To push the envelope further in spatial analytics, I am working with Dr. Sean Gallen to re-develop many of the routines offered in TopoToolbox into Python. The goal is to therefore transfer the utility of TopoToolbox into an environment that is free to the user, no matter the user's background within or outside of academia.

This project is currently in its early stages.
