# VCR-Synthetic

This repository contains the code and dataset information associated with the experiments reported in our ICPR paper:

Revisiting Vehicle Color Recognition in Long-Tailed Surveillance Scenarios
[pending link]

The project investigates synthetic data generation for Vehicle Color Recognition (VCR) under long-tailed and surveillance-like conditions. This repository includes the experimental code used for training and evaluation, as well as instructions for requesting access to the datasets.

# Code

The source code will be made available soon.

# Dataset

The released dataset is a two-part curated synthetic dataset for vehicle color recognition:

VCR-RunDiff, generated with RunDiffusion/Juggernaut-XL using text-to-image prompts.
FGVC-Gemini, generated with Gemini 2.0 Flash using image-conditioned generation based on vehicle images from UFPR-VeSV.

The dataset construction protocol, curation process, and initial experimental results are described in our paper.

## VCR-RunDiff

VCR-RunDiff contains 12,951 synthetic vehicle images generated through a text-to-image pipeline using RunDiffusion/Juggernaut-XL.

This subset was designed to increase the availability of samples for vehicle color recognition, especially for underrepresented color categories. However, images do not necessarily reproduce the visual of real-world vehicles and scenarios.

## FGVC-Gemini

FGVC-Gemini was generated with an image-to-image strategy using Gemini 2.0 Flash. The generation process was conditioned on images from the [UFPR-VeSV](https://github.com/Lima001/UFPR-VeSV-Dataset) dataset, which was kindly made available by its authors.

Unlike purely text-generated images, FGVC-Gemini was designed to preserve characteristics of real surveillance scenarios, including vehicle viewpoint, occlusion and visuals.

The UFPR-VeSV dataset contains vehicle images collected under diverse capture conditions, including frontal and rear views, daytime and nighttime acquisition, and infrared imagery. Since FGVC-Gemini is derived from UFPR-VeSV images, access to this subset follows the same academic and non-commercial restrictions required by the original dataset.

# How to Obtain the Dataset

Licensing under construction.

# Citation 

To be added. 
