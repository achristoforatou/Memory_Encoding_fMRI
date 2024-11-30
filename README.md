# Memory Encoding fMRI Visualization

**Name**: Angeliki Christoforatou  
**Date**: 30/11/24  
**Course**: Programming for Psychologists 2024/25  
**Course Code**: M_PROPSY  
**Course Coordinator**: Matthias Nau  
**Teaching Assistant**: Anna van Harmelen  

The data used in this code can be found on [Neurosynth](https://neurosynth.org). Specifically, the data related to memory encoding can be found [here](https://neurosynth.org/analyses/terms/memory%20encoding/).

## Project Description

This is an assignment for the **Programming for Psychologists** course in the Master's Program in Cognitive Neuropsychology at Vrije Universiteit Amsterdam. This project visualizes brain activity related to memory encoding using fMRI data from Neurosynth. The functional fMRI data were plotted on top of an anatomical brain scan to show regions activated during memory encoding, and a histogram was created to display the distribution of activation values across different brain areas.

## Table of Contents

1. [Data Used](#data-used)
2. [Notebook File](#notebook-file)

  ### Data Used
  
  This project uses fMRI data related to memory encoding from Neurosynth. It includes one data file containing the functional fMRI data and another containing the anatomical brain scan.
  
  - **memory encoding_uniformity-test_z_FDR_0.01.nii** (Functional fMRI data)
  - **anatomical.nii** (Anatomical brain scan)
  
  ### Notebook File

  - **Angeliki_Christoforatou_Memory_Encoding_fMRI.ipynb**: The Jupyter notebook that visualizes the functional MRI data on top of an anatomical brain scan.

## Python Packages

This project uses the following Python packages:

- **os**
- **glob**
- **nilearn**
- **matplotlib**
- **nibabel**
- **numpy**

This project was developed using **Python 3.12.4**.
