---
layout: page
title: GPT_GNN_3D_partitioner
description: A GPT-GNN based verilog netlist partitioner for 3D IC design
img: assets/img/GPT-GNN.png
importance: 10
category: work
related_publications: true
---

Repository: <a href="https://github.com/azwad-tamir/gpt_gnn_3D_partitioner">GitHub</a>

<p><strong style="font-size: 18px;">Description: </strong></p>

In this project, a Generative Pretrained Graph neural network has been utilized to develop a gate-level circuit partitioner for 3D IC design. The tool could be implemented to generate an end-to-end pipeline for the physical design of 3D ICs for the manufacture of next-generation ICs. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/GPT-GNN.png" title="GPT-GNN_Image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    GPT-GNN pre-training and fine-tuning.
</div>

As the channel length of modern IC technology shrinks down to nanometer scale, it is no longer possible to keep up with the trend of increased performance of digital ICs like processors and GPUs with transistor dimensionality reduction alone. This warrants a paradigm shift and one of the most promising advances that is likely to take up central stage is three dimensional ICs. Already several 3D IC technologies have been proposed in the scientific community but with the lack of fully automated 3D commercial P&R tool, it is very difficult to fabricate and test these ICs in the real world. 

The purpose of this project is to develop a partitioner tool using deep learning which would be able to segment a gate level netlist into multiple tiers to facilitate the implementation of 3D IC physical design. After the netlist has been partitioned, any conventional 2D IC design tool like the Synopsys ICC2 could be used to realize the full 3D IC physical design. First, the gate-level Verilog netlist is converted into a graph with the nodes representing the standard cells and the edges representing the connections between them. Then, a deeplearning framework named GPT-GNN (Generative Pre-Training of Graph Neural Networks) is used to latent vector representation of the input graphs. 

The node features used in the model are timing variables like worst slack, pin slew and worst delay while the edge features include the distance between each standard cell instances in the 2D version of the placement. Other features like module hierarchy information and n hop neighbors could also be put into the model as necessary. The resulting latent vectors are then used to partition the graph into n tiers.

ref: {% cite 3D_IC_design %}
