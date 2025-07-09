---
layout: page
title: ProtEC
description: A Transformer Based Deep Learning System for Accurate Annotation of Enzyme Commission Numbers
img: assets/img/ProtEC_pic1.JPG
importance: 10
category: work
related_publications: true
---
<p><strong style="font-size: 18px;">Paper Link</strong></p>
<a href="https://azwad-tamir.github.io/assets/pdf/ProtEC.pdf">ProtEC: A Transformer Based Deep Learning System for Accurate Annotation of Enzyme Commission Numbers</a>

Paper ref: {% cite ProtEC %}

<p><strong style="font-size: 18px;">Description: </strong></p>

In this project a transformer based Deep Learning model has been developed that could predict the Enzyme commission Numbers of Enzymes from full scale sequences. The input of the model are full-scale enzyme protein sequences and the output are the four EC numbers.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ProtEC_pic.JPG" title="ProtEC_Image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Data Flow of the training loop for the ProtEC model; Right: A Block diagram of the overall archtiecture of the ProtEC model.
</div>

<p><strong style="font-size: 18px;">Model: </strong></p>

The model consists of four modified ProtBert modules which has been slectively finetuned to achieve state of the art accuracy on EC numbers. The model has been trained on the Uniprot Swissprot reviewed dataset on two types of splits: The first one is called the random split, which randomly divides the data into train, validation and testing sets. Whereas, the second type is called clustered split, where the data has been split using UNIREF to make sure that the training and testing splits consists of different distributions of sequences.

<p><strong style="font-size: 18px;">Results: </strong></p>

The model has been compared with Proteinfer by Goodle and performs better in terms of accuracy and F1 scores. Moreover, the model is able to retain very high accuracy even when the training dataset is shrunk to 10% of its original size making it suitable in applications with very low amount of data. Fruthermore, the model accuracy is independant of sequence length so it is able to preform with very long or short sequences. Lastly, the model tunes most of its hyperparameters by itself so it is easy to use and does not require a separate validation set in order to train.

Dataset link: <a href="https://drive.google.com/file/d/1bZD67DqXv9LkYo0HCCEXW4USjgjgqBAY/view?usp=sharing">https://drive.google.com/file/d/1bZD67DqXv9LkYo0HCCEXW4USjgjgqBAY/view?usp=sharing</a> 

Trained models link: <a href="https://drive.google.com/file/d/1ObwqMIGE6A-gjr3lOTjaAWDhP0kbsJjL/view?usp=sharing">https://drive.google.com/file/d/1ObwqMIGE6A-gjr3lOTjaAWDhP0kbsJjL/view?usp=sharing</a> 
