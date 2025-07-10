---
layout: page
title: Anemia Detection
description: Detection of anemia from image of the anterior conjunctiva of the eye using image processing and thresholding.
img: assets/img/publication_preview/eye_image.jpg
importance: 10
category: work
related_publications: true
---

<p><strong style="font-size: 18px;">Paper Link</strong></p>
<a href="https://azwad-tamir.github.io/assets/pdf/Anemia_paper.pdf">Detection of Anemia from Image of the Anterior Conjunctiva of the Eye by Image Processing and Thresholding</a>

Paper ref: {% cite Anemia_paper %}

<p><strong style="font-size: 18px;">Description: </strong></p>

In this project, we have developed a lightweight and user-friendly tool to detect if a patient is anemic from images of the anterior conjuctiva of the eye. The system analyzes the rgb spectrum of the images of the eye to detect the level of anemia in a patient. The tool could be implemented in a smartphone with a camera and could deliver results instantaneously.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/anemia1.JPG" title="anemia1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Anterior conjuctiva of the eye
</div>


The World Health Organization (WHO) identifies anemia, a health hazard condition marked by the deficiency of red blood cells or hemoglobin in the bloodstream, affecting a quarter of the total world population. An automated, quick, and reliable detection of anemia is hence imperative. Preliminary detection of anemia is usually undertaken visually by the physician by examining the color of the anterior conjunctiva of the eye, and confirmed with an invasive blood test. In this study, we designed a mechanism for the automated detection of anemia through a  non-invasive visual method. Our process involves the detection of anemia by analyzing the anterior conjunctival pallor of the eye. It operates by quantifying the conjunctival color from digital photographs of the eye taken with a smartphone camera of appropriate resolution under adequate lighting conditions with the help of an Android application that we have devised. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/anemia2.JPG" title="anemia2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    RGB spectrum of an Anemic patient
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/anemia3.JPG" title="anemia3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    RGB spectrum of a non-anemic patient
</div>

These images are then processed to obtain the red and green component spectra of the conjunctiva color and compared against a threshold to determine whether the patient is anemic or not. We employed our method on 19 test subjects with known hemoglobin levels. The results obtained from our process agreed with the patient’s blood report in 15 out of the 19 cases, which translates to an accuracy of 78.9 percent. Our study was aimed towards the automation of healthcare facilities in underdeveloped parts of the world lacking proper healthcare facilities like hospitals and healthcare centers. Thus, we developed a computerized, noninvasive, simple, cost effective, easy-to-use, and portable primary screening test for anemia, which can provide a viable alternative to invasive methods of anemia detection and have a major humanitarian impact in the underdeveloped areas of the world.

