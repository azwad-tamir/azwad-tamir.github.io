---
layout: page
title: ProtGO
description: A Transformer based Fusion Model for accurately predicting Gene Ontology (GO) Terms from full scale Protein Sequences
img: assets/img/ProtGO_pic.JPG
importance: 3
category: work
related_publications: true
---

Repository: <a href="https://github.com/azwad-tamir/ProtGO">GitHub</a>

<p><strong style="font-size: 18px;">Paper Link</strong></p>
<a href="https://azwad-tamir.github.io/assets/pdf/ProtGO.pdf">ProtGO: A Transformer based Fusion Model for accurately predicting Gene Ontology (GO) Terms from full scale Protein Sequences</a>

Paper ref: {% cite ProtGO %}

<p><strong style="font-size: 18px;">Description: </strong></p>

In this project, a transformer based parallal modular fusion model has been developed that could predict the Gene Ontology (GO Terms) of proteins from full-scale sequences. The input of the model is full-scale enzyme protein sequences, and the output is the four EC numbers.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ProtGO_pic.JPG" title="ProtGO_Image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A Block diagram of the overall architecture of the ProtGO model.
</div>


Recent developments in next-generation sequencing technology have led to the creation of extensive, open-source protein databases consisting of hundreds of millions of sequences. To render these sequences applicable
in biomedical applications, they must be meticulously annotated by wet lab testing or by extracting them from
existing literature. Over the last few years, researchers have developed numerous automatic annotation
systems, particularly deep learning models based on machine learning and artificial intelligence, to address this issue. 

In this work, we propose a transformer-based fusion model capable of predicting Gene Ontology (GO)
terms from full-scale protein sequences, achieving state-of-the-art accuracy compared to other contemporary
machine learning annotation systems. The approach performs particularly well on clustered split datasets,
which comprise training and testing samples originating from distinct distributions that are structurally
diverse. This demonstrates that the model can understand both short and long-term dependencies
within the enzyme’s structure and can precisely identify the motifs associated with the various GO terms.
Furthermore, the technique is lightweight and less computationally expensive compared to the benchmark
methods, while at the same time not being affected by sequence length, rendering it appropriate for diverse
applications with varying sequence lengths.


Dataset link: <a href="https://drive.google.com/file/d/19SXO7Asy2vsAab6cl36-IkUqq9DYMgDb/view?usp=sharing">https://drive.google.com/file/d/19SXO7Asy2vsAab6cl36-IkUqq9DYMgDb/view?usp=sharing</a> 

