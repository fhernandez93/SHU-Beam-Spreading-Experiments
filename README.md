This repository contains code and simulation notebooks for analyzing the transverse spreading of a focused electromagnetic beam propagating through two-dimensional disordered photonic slabs. By measuring the evolution of intensity in the time and frequency domains, we identify distinct transport regimes — including ballistic, diffusive, Lifshitz (bandgap-dominated), and Anderson localized behaviors.

## Project Overview

This project performs finite-difference time-domain (FDTD) simulations on hyperuniform disordered structures to:

- Launch a narrowband focused beam into a 2D dielectric slab
- Compute intensity profiles at different propagation depths
- Record time-domain field evolution

The simulations and analysis demonstrate how disorder strength and hyperuniformity govern wave transport, allowing a quantitative extraction of localization and diffusive signatures.

## Repository Contents

```
Time Domain Experiments.ipynb    → Main analysis notebook
structures/                      → point patterns to analyze
README.md                        → project description
```

## Scientific Motivation

Hyperuniform disordered photonic materials are known to exhibit unusual optical transport mechanisms, including diffusion and Anderson localization. However, experimental and numerical identification of these regimes has historically relied on transmission spectra or eigenmode analysis.

## License

MIT License

