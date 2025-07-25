# Demonstrating Monty Capabilities Experiments (DEPRECATED)

==== DEPRECATION ====

This directory contains intitial configs and scripts for early work on the "DMC" paper. It has been deprecated and anyone interested in replicating the results of our paper, "Thousand-Brains Systems: Sensorimotor Intelligence for Rapid, Robust Learning and Inference", should refer to the repository here https://github.com/thousandbrainsproject/tbp.tbs_sensorimotor_intelligence

=====================

This repository contains the code for the experiments in the paper "Demonstrating Monty Capabilities".

## Setup

The results of DMC experiments are stored under `DMC_ROOT_DIR`. By default, this is `~/tbp/results/dmc`, but you can change this by setting the `DMC_ROOT_DIR` environment variable. It has the following structure:

```
DMC_ROOT_DIR/
    pretrained_models/
    results/
    view_finder_images/
    visualizations/
```

The `pretrained_models` directory contains the pre-trained models for Monty experiments. The `results` directory contains the results of evaluation experiments. The `view_finder_images` directory contains the images used for input to ViT-based models as well as for some figure visualizations.

Figures and tables are stored under `DMC_ANALYSIS_DIR`. By default, this is `~/tbp/results/dmc_analysis`, but you can change this by setting the `DMC_ANALYSIS_DIR` environment variable.

## Running the Experiments

Configs to train models and run experiments are in the `configs` directory.

## Reproducting Figures from the Paper

Analaysis scripts to generate the figures are in the `scripts` directory. The data for figures can either be generated via `configs`, or you can directly download the pre-trained models at `link-to-be-confirmed` and the raw results from experiments at `link-to-be-confirmed`.
