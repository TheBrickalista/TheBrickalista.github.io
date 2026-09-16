---
layout: page
title: PyMicRheo
description: Python application for magnetic tweezer microrheology and viscoelastic analysis.
importance: 6
category: software
# img: assets/img/projects/pymicrheo.jpg
---

PyMicRheo is a desktop graphical application written in Python, developed for magnetic tweezer microrheology experiments. It analyses the motion of magnetic beads pulled by magnetic forces to extract the viscoelastic properties of biological samples.

The analysis workflow covers the full path from raw data to viscoelastic parameters: force calibration, drift correction and artefact cleaning, trajectory analysis using principal component analysis, and fitting of viscoelastic models to the resulting bead trajectories.

PyMicRheo is developed alongside [Magzy]({{ '/projects/magzy/' | relative_url }}), the LEGO®-based magnetic tweezers system built in the lab, and is intended to process the microrheology data it produces.

The application is currently in development, and its code has not yet been publicly released.

<!-- TODO: add repository link and screenshots once released -->

{% comment %}
{% include figure.liquid path="assets/img/projects/pymicrheo.jpg" title="PyMicRheo" class="img-fluid rounded z-depth-1" %}
{% endcomment %}
