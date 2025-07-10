---
layout: page
title: SPAD Performance Modelling
description: Modelling of Performance Parameters of Single Photon Avalanche Detector Incorporating Dead Space Effects and History Dependent Ionization Coefficient
img: assets/img/SPAD.JPG
importance: 10
category: work
related_publications: true
---

<p><strong style="font-size: 18px;">Paper Link</strong></p>
<a href="https://azwad-tamir.github.io/assets/pdf/SPAD.pdf">Modelling of Performance Parameters of Single Photon Avalanche Detector Incorporating Dead Space Effects and History Dependent Ionization Coefficient</a>

Paper ref: {% cite SPAD %}

<p><strong style="font-size: 18px;">Description: </strong></p>

This work studies the performance parameters of Single Photon Avalanche Detectors (SPADs) while considering the effects of Dead Space regions and history-dependent Ionization Coefficient. The mathematical model of the SPAD has been developed and simulated to extract the performance features of the device under different conditions.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SPAD.JPG" title="SPAD_Image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Dead space profile for electrons and holes at V = 75 V & 105 V
</div>

<p><strong style="font-size: 18px;">Model: </strong></p>

The modelling and simulation of the performance parameters of a single-photon avalanche diode (SPAD) is carried out with the help of MATLAB. The model is applied to a sample SAM SPAD device, which consists of a multiplication region made of InP and an absorber region of InGaAs. A generalized theory for breakdown probability is implemented, which takes into account the generation of photocarriers at random locations within each layer. The study reveals that by increasing the multiplication region width, the number of dark carriers due to field-assisted generation mechanisms is reduced, which is counteracted by an increase in the number of GR dark carriers. 

Thus, the photon detection efficiency (PDE) and Dark count rate (DCR) are of utmost importance before the fabrication of a device. In this work, we have simulated a SPAD device incorporating dead space effects and history-dependent ionization coefficient to generate the electric field profile, dead space profile, ionization coefficient profile, breakdown profile, and avalanche probabilities. Finally, we have extracted the PDE vs. over bias voltage and PDE vs DCR curves of the simulated device under different multiplication region widths to demonstrate the effect of multiplication region width on the performance parameters of a SPAD.
