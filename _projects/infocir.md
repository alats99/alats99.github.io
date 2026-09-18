---
layout: page
title: InfoCIR
description: Visual analytics for composed image retrieval. PacificVis 2026.
img: assets/img/infocir.jpg
importance: 1
category: research
---

**InfoCIR** is a visual analytics system for composed image retrieval (CIR): searching with a reference image plus a text prompt that describes the desired change.

The interface couples retrieval, explanation, and prompt refinement. Users can inspect UMAP embeddings of the query and top-k results, overlay saliency maps and token attributions, and use an LLM-based prompt enhancer to see how small wording changes move the ranking.

Joint work with Ioannis Dravilas, Ioannis Kapetangeorgis, Conor McCarthy, Gonçalo Marcelino, and [Marcel Worring](https://www.uva.nl/en/profile/w/o/m.worring/m.worring.html) at the University of Amsterdam. Published at IEEE PacificVis 2026.

**Links:** [paper](https://arxiv.org/abs/2602.13402) · [code](https://github.com/giannhskp/InfoCIR)

{% include figure.liquid path="assets/img/infocir.jpg" title="InfoCIR dashboard" class="img-fluid rounded z-depth-1" %}
