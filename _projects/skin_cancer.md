---
layout: page
title: Transfer_ViT
description: Studying Cross-Transferability of Vision Transformers using HAM10000 skin cancer dataset.
img: assets/img/Skin_cancer_pic.jpg
importance: 10
category: work
related_publications: true
---

Repository: <a href="https://github.com/azwad-tamir/Transfer_ViT">GitHub</a>

<p><strong style="font-size: 18px;">Article Link</strong></p>
<a href="https://medium.com/machine-intelligence-and-deep-learning-lab/studying-cross-transferability-of-vision-transformers-using-ham10000-skin-cancer-dataset-1b5820653554">Studying Cross Transferability of Vision Transformers using HAM10000 skin cancer dataset</a>

<p><strong style="font-size: 18px;">Description: </strong></p>

The objective of this study is to determine if there are significant advantages to applying transfer learning when the two datasets involved are different in nature. Also, we would investigate whether it is better to train the model in a conventional way directly on the application dataset without transfer learning if pretrained models similar to the application dataset could not be found.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Skin_cancer_pic.jpg" title="Transfer_ViT_Image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Architectural Block diagram of the original ViT model.
</div>

The number of learnable parameters of deep learning models have risen substantially in recent years. Some very large deep learning models can contain more than 10^13 parameters which require a long time, many GPUs, and a large dataset containing many datapoints to train effectively. However, there are many practical situations where such resources are not readily available. For example, in bioinformatics, datapoints have to be labeled using domain experts making large datasets scarce and often not made open source. One solution to this problem is through Transfer learning which involves training a model twice on two different datasets. The process is made up of two steps. First is the pretraining step which involves training the model on a large opensource dataset. The next step is finetuning, where the pretrained model is finetuned on the smaller application dataset. Finetuning could be done in two ways: 1) All the model parameters are updated during the finetuning process; 2) The initial layers of the model are frozen and only the layers towards the end are updated. The latter process is more widely accepted and would be used in this study.

One of the limitations of transfer learning is that the two datasets involved in the transfer learning process should be similar in nature. Otherwise, problems such as negative learning and overfitting may occur. However, getting a model which is pretrained on a dataset similar to the application dataset is often not an option.

The cross-transferability attribute of the following models have been investigated in this project:<br />
1) VGGNet19bn
2) ResNet152
3) DenseNet
4) InceptionV3
5) ViT_base
6) DeepViT_base
7) CaiT_base
8) T2TViT_base
9) ViT_pretrained
10) DeiT_pretrained
11) BeiT_pretrained
12) 
