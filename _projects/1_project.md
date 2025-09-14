---
layout: page
title: Marketing Digital Outdoor (MDO)
description: marketing scenting device with video and audio capabilities
img: assets/img/hw-all-crop.jpg
importance: 1
category: work
related_publications: false
---

The Marketing Digital Outdoor (MDO) is a marketing scenting device with video
and audio capabilities which allows the user to interact with the device through
hand gestures.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager"
    path="assets/img/hw-all-crop.jpg" title="MDO prototype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    MDO prototype
</div>


--- 

## Features [10/10]
1. [X] Advertising through a screen and speakers;
2. [X] Have fragrance diffusion;
3. [X] Take pictures and GIFs;
4. [X] Detect a user in range of the device;
5. [X] Contactless user interaction through gesture recognition;
6. [X] Camera feed and facial detection;
7. [X] Apply brand-specific image filters;
8. [X] Enable sharing multimedia across social media;
9. [X] Provide a remote user interface for brands to purchase and configure the advertisements;
10. [X] Provide a remote user interface for company staff to monitor and control the MDO local system.

--- 

## Technologies [13/13]
1. [X] Computer vision for facial and gesture recognition (OpenCV)
2. [X] Database for marketing digital outdoor management (SQL)
3. [X] Website/Application for brands communication to our database
4. [X] Wireless communication technology for remote communication with digital outdoors
5. [X] Image filter application
6. [X] Infrared detection
7. [X] Camera recording
8. [X] Audio output
9. [X] Nebulizer technology for scenting
10. [X] Screen mapping to keys for virtual keyboard
11. [X] Social media and e-mail sharing APIs
12. [X] Embedded Linux to support the device features
13. [X] Qt for UI development

---

# HW architecture


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager"
    path="assets/img/hw-arch.jpg" title="HW arch overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    HW architecture overview
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager"
    path="assets/img/hw-arch-complete.jpg" title="HW architecture mapping" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    HW mapping
</div>

---

# SW architecture

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager"
    path="assets/img/sys-overview.jpg" title="SW architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    SW architecture
</div>

---

# References
- https://github.com/ElectroQuanta/MDO
