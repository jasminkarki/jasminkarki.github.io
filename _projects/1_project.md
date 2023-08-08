---
layout: page
title: Wi-Fi CSI based Human Activity Recognition
description: Recognize human activity(walk, run, idle) using Wi-Fi channel state information obtained from low cost microcontroller, ESP32
img: assets/img/har_data_collection.png
importance: 1
github: https://github.com/jasminkarki/Wifi-Sensing-HAR
category: work
# related_publications: einstein1956investigations, einstein1950meaning
---

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: Wi-Fi CSI based Human Activity Recognition
    description: Recognize human activity using Wi-Fi CSI
    img: /assets/img/12.jpg
    ---

Device-free Wi-Fi sensing is widely facilitated by the prevailing Linux CSI tool designed for the Intel 5300 Network Interface Card (NIC). However, this tool is constrained by the necessity of a laptop equipped with the specific Intel 5300 NIC card. Moreover, the utilization of the Intel 5300 NIC card is hindered by its inherent drawback of furnishing CSI data solely for 30 out of the 52 subcarriers within a 20 MHz bandwidth.

Implementation of a real-time human activity recognition system by employing signal processing techniques on
the Wi-Fi CSI obtained from ESP module fed to an ML model to recognize walking, jogging, and idle activity.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/amp_walk.jpg" title="Amplitude vs time across subcarrier while walking" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/amp_jog.jpg" title="Amplitude vs time across subcarrier while jogging" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Amplitude Variation with time in different activities
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}

