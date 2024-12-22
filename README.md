# Deblurring Optically Distrted Dataset

This is the code for a project for my summer internship done at colorlab in NTNU in Gjøvik. 

## Introduction
Optical aberrations pose significant challenges in the field of image quality assessment and enhancement. The Colourlab Image Dataset: Optical Aberrations (CID:OA), introduced recently, provides a comprehensive collection of images with various optical distortions, such as defocus, vertical astigmatism, and spherical aberrations, at four distinct levels each.

In this project, we evaluated multiple conventional and deep learning-based image enhancement techniques on the CID:OA dataset to understand their effectiveness in mitigating optical distortions. Additionally, the models were tested on blurred images from the TID2013 dataset, which includes Gaussian blur across five different levels, enabling us to compare their performance across datasets with different distortion characteristics.

## Evalauated Methods
**Conventional Methods**
1. [Blind Image Deblurring Using Patch-Wise Minimal Pixels Regularization](https://github.com/FWen/deblur-pmp) under PMP folders.
2. [Enhanced Sparse Model for Blind Deblurring](https://liangchen527.github.io/) under ESModel folders.
3. [A semi-blind deconvolution method to estimate and remove optical aberrations](https://www.sciencedirect.com/science/article/pii/S003040262400113X)

**Deep-Learning Based Models**
1. [Simple Baselines for Image Restoration](https://github.com/megvii-research/NAFNet) under NAFNet folders.
2. [Learning to Deblur using Light Field Generated and Real Defocused Images](https://github.com/lingyanruan/DRBNet) under DRBNet folders. 
3. [Multi-Stage Progressive Image Restoration](https://github.com/swz30/MPRNet) under MPRNet folders.
4. [Revisiting Image Deblurring with an Efficient ConvNet](https://github.com/lingyanruan/LaKDNet) under LaKDNet folders.
5. [Learning Single Image Defocus Deblurring with Misaligned Training Pairs](https://github.com/liyucs/JDRL) under JDRL folders.
6. [Efficient Transformer for High-Resolution Image Restoration](https://github.com/swz30/Restormer) under Restormer folders.
7. [Stripformer: Strip Transformer for Fast Image Deblurring](https://github.com/pp00704831/Stripformer-ECCV-2022-) under Stripformer folders.
8. [Rethinking Coarse-to-Fine Approach in Single Image Deblurring](https://github.com/chosj95/MIMO-UNet) under MIMOUnet folders.

## Evalauation Metrics
Metrics such as **MSSIM**, **FSIM**, **PSNR**, **LPC** **BRISQUE**, **CPBD**, and **JNB** were used to quantitatively assess the deblurred images' quality.

