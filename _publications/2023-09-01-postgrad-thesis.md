---
title: "Reproducible Knowledge Distillation for Graph Neural Networks"
collection: publications
category: thesis
permalink: /publication/2023-09-01-postgrad-thesis
excerpt: 'This thesis introduces RepKD, a reproducibility-aware knowledge distillation framework for graph neural networks that preserves model performance while improving reproducibility.'
date: 2023-09-01
venue: 'Imperial College London'
slidesurl: 'https://lorenzostigliano.github.io/files/thesis/grad_thesis_slides.pdf'
paperurl: 'https://lorenzostigliano.github.io/files/thesis/grad_thesis.pdf'
citation: "L. G. Stigliano, I. Rekik (2023). <i>Reproducible Knowledge Distillation for Graph Neural Networks</i>. Master’s thesis, Imperial College London."
---
Graph Neural Networks (GNNs) are powerful models for graph-structured data but face scalability challenges that hinder deployment in real-time and resource-constrained settings, motivating the use of knowledge distillation on graphs (KDG) to compress models while preserving performance; however, existing approaches largely overlook reproducibility, a key requirement for trustworthy model interpretation. In this work, we introduce the concept of reproducible offline knowledge distillation for GNNs and show that standard KD and KDG methods often degrade reproducibility. To address this, we propose Reproducibility-aware Knowledge Distillation on Graphs (RepKD), a two-stage framework that jointly trains multiple student models in a one-to-many teacher–student setup and selects the most reproducible student. Across multiple datasets and GNN architectures, RepKD improves self-reproducibility while maintaining predictive performance, achieving over 95% parameter reduction with negligible memory overhead and comparable training times, and we further explore the interpretability of the resulting distilled models.