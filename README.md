# FutureMotion
Common repo for our ongoing research on motion forecasting in self-driving vehicles.

## RedMotion: Motion Prediction via Redundancy Reduction
TL;DR: Transformer model for motion prediction that incorporates two types of redundancy reduction.


### Overview
![RedMotion](figures/red_motion.png "RedMotion")

**RedMotion.** Our model consists of two encoders. The trajectory encoder generates an embedding for the past trajectory of the current agent. The road environment encoder generates sets of local and global road environment embeddings as context. We use two redundancy reduction mechanisms, (a) and (b), to learn rich representations of road environments. All embeddings are fused via cross-attention to yield trajectory proposals per agent.

### Getting started
Coming soon!

This repo contains the refactored implementation of RedMotion, the original implementation is available [here](https://github.com/kit-mrt/red-motion).


## Acknowledgements
This repo builds upon the great work [HPTR](https://github.com/zhejz/HPTR) by [@zhejz](https://github.com/zhejz). 
