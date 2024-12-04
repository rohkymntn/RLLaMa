# PharmaLLaMA: Transformer-Based Molecular Generator with PPO

## Overview

PharmaLLaMA is a state-of-the-art generative AI model designed to create novel drug-like molecules in **SELFIES** format, optimized for specific properties.  The model will attempt to optimize an input
molecule, described as a Self-Referencing Embedded String (SELFIES) format, towards desired
chemical properties outputting a novel optimized molecule. In this case study, we used JAK2
inhibition as an optimization parameter. Built on Meta's **LLaMA** transformer architecture, the model integrates **Proximal Policy Optimization (PPO)** to refine molecular generation, advancing the field of de novo drug design.

This project demonstrates how transformer-based architectures and reinforcement learning can be combined to surpass traditional graph-based models and even some transformer based models
that were previously reported for molecular generation in producing highly valid, novel, and diverse molecules suitable for experimental validation.
