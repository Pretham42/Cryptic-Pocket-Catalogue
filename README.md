# Cryptic Pocket Catalogue

A website that shows where proteins may hide a drug pocket.

A cryptic pocket is closed in the structures we have and only opens when a drug arrives, so docking and screening usually miss it. This catalogue predicts where such pockets are in 18,336 human proteins and helps you find the ones worth a closer look.

## What you can do

- Choose a starting list, then switch gates on and off. The gates are a strong disease link, not a recessive disease, not already drugged and a cysteine within reach. A bar chart shows how many proteins each gate removes.
- Click a row to open the protein in 3D. The predicted pocket is violet.
- Watch real simulations of ten runs. Each one shows the pocket at the start and at its most open moment.
- Look at an exploratory docking example for TRIB1, a protein linked to acute myeloid leukaemia.

## Try it

The page loads its data files, so open it through a small web server.

```
python3 -m http.server
```

Then go to http://localhost:8000 in your browser. The 3D viewer and the protein structures come from the internet, so you need to be online.

## What it is not

Everything here is a prediction or a simulation. Nothing shows that a molecule binds, and no pocket on this page has been confirmed in the lab.

## Data and credits

Structures come from the RCSB Protein Data Bank and the AlphaFold Protein Structure Database. Sequences and annotations come from UniProt. Disease links come from Open Targets and development levels from Pharos. The 3D viewer is 3Dmol.js. Please follow each source's own terms of use.

## About

An independent research project from 2026. It was built with the help of an AI coding assistant (Claude Code). The research questions, the choices and the checking are the author's.
