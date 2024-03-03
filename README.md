# Reverse-engineering SAE features in GELU-1L with transcoders

This repository contains a Jupyter Notebook that demonstrates how to reverse-engineer SAE features in a one-layer language model using transcoders. This is an interim product of current work at MATS 5.0; as such, it might be a bit rough around the edges.

## Installation

You'll want to clone this repo, including the transcoder and SAE weights. Then, in a separate directory, clone [my fork of Joseph Bloom's SAE library which adds transcoder support](https://github.com/jacobdunefsky/mats_sae_training). After cloning it, move the `sae_training` directory in that repo to the same directory in which the Jupyter Notebook is located. Oh, and make sure to install all the requirements for the Jupyter Notebook itself, too.
