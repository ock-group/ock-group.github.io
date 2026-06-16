---
title: Research
nav:
  order: 1
  tooltip: Research Projects
---

# {% include icon.html icon="fa-solid fa-flask-vial" %} Projects

{% include search-info.html %}

Molecular and materials design is a high-dimensional search problem where composition, structure, and processing conditions are deeply coupled. Traditional approaches rely on researchers' intuition to define search spaces and iteratively adjust candidate generation and simulation settings — a sequential, labor-intensive process. We aim to overcome these limits by building AI agent systems that integrate search space definition, candidate generation, computation, and decision-making into a unified autonomous loop.

Our research sits at the intersection of large language models (LLMs), agent design, and multimodal learning, with the goal of establishing general-purpose agent methodologies applicable across molecular and materials design problems. We pursue this through three core directions:

## Cognitive Mechanisms of Agents for Chemical Reasoning

We investigate how LLMs encode chemical knowledge and constraints in latent space, and how these representations connect to reasoning and performance. This includes quantitative analysis of embedding structures for molecular representations and functional groups, and understanding how memory design and agent architecture shape search behavior. Our goal is to establish principled design rules for agents optimized for materials application.

## Multimodal Foundation Models for Experiment–Computation Integration

We develop foundation models that jointly understand electron microscopy images, spectroscopic data, synthesis conditions, and text records. Combined with agent frameworks, these models can predict properties from experimental inputs, quantify uncertainty, and autonomously propose follow-up experiments — such as additional characterization or synthesis adjustments — to resolve ambiguities and guide discovery.

## Nano-Scale Self-Assembly Modeling

We model self-assembled nanonetworks — predicting dynamic percolation pathways and the nonlinear, non-Ohmic electrical response that emerges as nanoparticles organize into conductive structures. Our current foundation is a physics-based solver, on top of which we are developing graph neural networks, generative models, and GFlowNet-based sampling to invert the problem — engineering network structures that meet target properties. A central direction is scaling these models from the atomic scale to the nanoscale, the regime critical for device-level development of next-generation nanoelectronics.