---
layout: page
title: PysternBlot
description: Open-source Python app for Western blot figures with provenance tracking.
importance: 5
category: software
github: https://github.com/TheBrickalista/PysternBlot
# img: assets/img/projects/pysternblot.jpg
---

Western blot figures are typically assembled through a chain of general-purpose image editing tools, which makes it hard to trace how the final figure relates to the original raw data. [PysternBlot](https://github.com/TheBrickalista/PysternBlot) addresses this by keeping a traceable link between the raw images and the final figure throughout the whole process. It supports near-infrared (NIR) fluorescence imaging, including Cytiva Typhoon scanners, alongside standard workflows.

Analyses can be exported and imported as `.pbarchive` files, a dedicated archive format designed to share and archive complete analyses, including the raw data and the processing history that led to the final figure. This makes it easier to hand off an analysis to a collaborator, or to keep a long-term, self-contained record of how a published figure was produced.

PysternBlot is distributed on PyPI as [`pysternblot`](https://pypi.org/project/pysternblot/), with prebuilt macOS and Windows applications, and is released under the GPLv3 license. It is co-developed with Chloé Féral and archived on Zenodo at [doi.org/10.5281/zenodo.20185279](https://doi.org/10.5281/zenodo.20185279).

{% comment %}
{% include figure.liquid path="assets/img/projects/pysternblot.jpg" title="PysternBlot" class="img-fluid rounded z-depth-1" %}
{% endcomment %}
