# Reverse-engineering SAE features in GELU-1L with transcoders

This repository contains a Jupyter Notebook that demonstrates how to reverse-engineer SAE features in a one-layer language model using transcoders. This is an interim product of current work at MATS 5.0; as such, it might be a bit rough around the edges.

## Installation

1. Clone this repo into some directory on your local machine.
2. Download all of the files [from this Google Drive folder](https://drive.google.com/drive/folders/1CyepXtramm9N1NL1D5LyabrGm7a2xQTz?usp=sharing) into the directory that you cloned this repo into; these files contain SAE/transcoder weights and feature sparsity information.
3. In a separate directory, clone [my fork of Joseph Bloom's SAE library which adds transcoder support](https://github.com/jacobdunefsky/mats_sae_training). After cloning it, move the `sae_training` directory in that repo to the same directory as everything else (the Jupyter Notebook, the SAE weights, etc.).
4. Make sure to install all the requirements for the Jupyter Notebook itself, too.

## Usage

Run the Jupyter Notebook `reverse_engineering.ipynb`, making sure that the Python kernel is running from the same directory that the notebook is in.
