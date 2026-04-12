# Diffusion Model Tutorial

This folder uses a shorter teaching ladder:

1. [`diffusion-fundamentals.ipynb`](./diffusion-fundamentals.ipynb) - unconditional diffusion first, then conditional diffusion, then the bridge to materials.
2. [`crystal-diffusion-from-scratch.ipynb`](./crystal-diffusion-from-scratch.ipynb) - a lightweight crystal diffusion notebook built on top of the fundamentals.
3. [`sota-crystals-comparison.ipynb`](./sota-crystals-comparison.ipynb) - MatterGen first, then Chemeleon2 as the higher-complexity SOTA example.

## What each notebook is for

- **Diffusion fundamentals**: learn the dynamics, noise processes, flow matching, and score matching language once.
- **Crystal diffusion from scratch**: see how those ideas become a lightweight crystal generator with unconditional and conditional variants.
- **SOTA comparison**: compare a direct crystal diffusion system against a more modular VAE + latent diffusion + RL pipeline.

## Reading order

Start at the top and move downward. Each notebook is self-contained, but the later ones assume the earlier concepts are familiar.
