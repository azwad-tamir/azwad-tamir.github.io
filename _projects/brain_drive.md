---
layout: page
title: Brain-Drive
description: A Smart Driver for Controlling Digital Appliances Using Cognitive Command
img: assets/img/publication_preview/brain_drive.jpg
importance: 10
category: work
related_publications: true
---

<p><strong style="font-size: 18px;">Paper Link</strong></p>
<a href="https://azwad-tamir.github.io/assets/pdf/Brain-drive.pdf">Brain-Drive: A Smart Driver for Controlling Digital
Appliances Using Cognitive Command</a>

Paper ref: {% cite Brain-drive %}

<p><strong style="font-size: 18px;">Description: </strong></p>

This project involves the development of a wearable device that could harness the EEG signals from the wearer's brain to control various devices around the household. The signal processing is handled by a Raspberry Pi microprocessor that captures the signals wirelessly from the wearable device. The results show the potential to use the device to control wheelchairs, home appliances, and even industrial machines.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/publication_preview/brain-drive" title="brain_drive_img" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The developed wearable device prototype, along with the Raspberry Pi equipped with a display
</div>


The world of brain-computer interface has opened a new horizon for the disabled and handicapped to lead an unassisted and least supervised life. But the use of prosthetic limbs and artificial organs are still not commercially available in most of the countries. Recently developed some other brainwave based systems are mostly expensive, immobile or task specific. In order to overcome these problems, analogous to the pen-drive, we have focused on developing a low cost control unit namely “Brain-drive” which transforms ones thoughts into an output digital electric signal. Certain thoughts (mental tasks) with hard eye blinking (neural driven physical outcome) develops certain action potential, no matter the eye blinking is visible or not, it creates a significant change in electroencephalogram (EEG) or brain signal. Single channel EEG signal is collected from frontal lobe as it plays a vital role in voluntary movement using a wearable Mindwave Mobile from Neurosky. The EEG data thus recorded is preprocessed to reduce the effect of noise and artifacts and then analyzed in time domain. A grid of cells are displayed on a monitor in front of the subject, which is connected to individual digital output pin onboard an embedded system. To select a cell, a user just needs to look and generate a sustainable eye blink, which can easily be identified from the raw value of brainwave. Since eye blinking can be both conscious and involuntary, the automatic periodic eye blink of very low frequency oscillation is removed to avoid unwanted selection of command. Unlike webcam based eye blink detector, Brain-Drive captures the signal for blink rather than the visual output of blinking. The system can be trained for person specific customized performance, considering the special needs of a disabled or handicapped people who cannot communicate with the outside world using voice, motion, or other methods. With the help of cognitive command, the ‘Brain-Drive’ can be used to control wheelchair, home appliances, and even industrial machines.

