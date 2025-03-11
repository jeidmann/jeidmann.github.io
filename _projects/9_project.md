---
layout: page
title: temperature sensitive heat system
description: To limit fire hazards of a heat lamp in a quail coop, I designed and implemented a temperature-regulated heat lamp to keep our egg-laying girls warm.
img: assets/img/quail.png
importance: 3
category: fun
---

We love our quail, and want to provide them with a cozy little nook in our quail coop. However, adding a heat lamp can provide a fire danger--especially in Colorado! As a result, I created my own temperature-regulated heat lamp.

As a temperature sensor, I used the `ds18b20`, which I connected to an `Arduino` board. In the code, I specified how often I want the Arduino to check the temperature inside the coop (e.g. every 5 minutes), and what my desired threshold temperature should be, below which the lamp turns on. Note: I originally set the check time to every 10 seconds, but this created a 'disco-like' ambiance that I don't think any person or quail would appreciate.

When the sensor is checked and the temperature is below the given threshold, the Arduino provides power to a desired node, which leads to `5V relay`. This relay receives normal electric power, but only completes the circuit when given the message from the Arduino.

Using this setup, I am able to control the coop temperature throughout the winter and turn the light off when it is above a certain temperature. This way, the light will not continue to heat up to coop to the point that in poses an ignition risk.

<b> Happy <u> and</u> safe quail = lots of eggs all year long!</b>

<div class="row justify-content-sm-center">
    <div class="col-sm-4">
        {% include figure.liquid path="assets/img/Quail3.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4">
        {% include figure.liquid path="assets/img/QuailEggs.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
