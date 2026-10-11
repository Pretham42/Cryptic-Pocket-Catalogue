# Cryptic Pocket Catalogue

**Live site: https://pretham42.github.io/Cryptic-Pocket-Catalogue/**

![The catalogue, one protein in 3D, and a simulation](img/overview.png)

*The catalogue (a), one protein in 3D (b), and the same protein in a simulation at its first (c) and most open (d) frame.*

A website that shows where proteins may hide a drug pocket. A cryptic pocket is closed in the structures we have and only opens when a drug arrives, so docking and screening usually miss it. This catalogue predicts where such pockets are in 18,336 human proteins and helps you find the ones worth a closer look. Everything on it is a prediction or a simulation. It points to places worth testing, and nothing here shows that a pocket is real or that a molecule binds.

## What you can do

- **Narrow the list like a funnel.** Pick a starting list (the hidden pockets, the disease-linked proteins, or everything), then switch on the questions you care about. Each question removes the proteins that do not fit, and a bar chart shows how many it removed.
  - A strong disease link means a change in the protein is tied to a disease.
  - Not a recessive disease keeps out diseases that usually come from a missing or broken protein, which a pocket drug rarely fixes.
  - Not already drugged means no approved drug or potent compound exists yet.
  - A cysteine within reach means there is a cysteine next to the pocket, which gives a lab a handle to test it.
- Click a row to open the protein in 3D. The predicted pocket is violet.
- Watch real simulations of ten runs. Each one shows the pocket at the start and at its most open moment.
- Look at an exploratory docking example for TRIB1, a protein linked to acute myeloid leukaemia.

## Data and credits

Structures come from the RCSB Protein Data Bank and the AlphaFold Protein Structure Database. Sequences and annotations come from UniProt. Disease links come from Open Targets and development levels from Pharos. The 3D viewer is 3Dmol.js. Please follow each source's own terms of use.

## About

Independent research project from 2026. Website and code built with the help of Claude Code.
