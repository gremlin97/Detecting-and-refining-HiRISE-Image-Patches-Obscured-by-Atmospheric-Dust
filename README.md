## Detecting-and-refining-HiRISE-Image-Patches-Obscured-by-Atmospheric-Dust
#### HiRISE Dusty Patches Detector and Denoiser
Course: CSE 572

## Goal
This repository contains code for my CSE572: Data Mining Final Project. The goal of this project is to create an end-to-end pipeline to bifurcate dusty and non-dusty (Images obstructed by atmospheric dust from martian storms) image patches from the HiRISE camera. Further, we denoise the dusty patches to filter and generate denoised images.

## Dataset
Dataset url: https://zenodo.org/record/3495068#.Y6VYZHbMJPZ

## Folder Contents
* The codebase consists of an `'/Experiments'` folder where all the experimentation conducted during the Project Time Period is included. It also includes the SSIM, MSSIM, PSNR, and MAE metrics to calculate the difference between the denoised and expected images. 

* `Denoiser_mod.ipynb`: This notebook generates noisy training data, and uses it to train denoising models and display the results.
* `ResNetAtmosphericDustMars_main.ipynb`: This notebook trains and evaluates a Resnet50 classifier on the dataset.
* `DustPredictor.ipynb and AtmosphericDustMars_main.ipynb`: These notebooks contain our data loading, preprocessing, and visualization steps. They also contain our baseline models for classification.
* `p2pgan.ipynb`: Contains are Pix2Pix Denoiser.

## How to Run?

### Python Notebook
* First inspect then run the required individual IPYNB files `Denoiser_mod.ipynb, DustPredictor.ipynb etc.` files as per the task to get the required output.
* Run them in Colab or run the Jupyter notebook in your local instance. . For any issues regarding the code please mail me at: kkasodek@asu.edu.
