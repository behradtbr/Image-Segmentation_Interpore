# Multiphase Image Segmentation of Naturally and induced Fractured Media

This repository contains the research code related to the article:

**“Multiphase Image Segmentation of Naturally Fractured Media: Benchmarking Deep Learning and Conventional Approaches”**
Published in **InterPore Journal, Vol. 3, Issue 1, 2026**
DOI: **10.69631/j6zv1891**

## Overview

Image segmentation is a key step in digital rock physics workflows, especially for the characterization of naturally fractured reservoir rocks. Accurate segmentation of fractured media helps distinguish different rock and fracture phases, supports pore-scale analysis, and enables further investigation of petrophysical properties such as porosity, permeability, and fracture connectivity.

This repository provides the research code used for multiphase image segmentation of naturally fractured rock samples. The workflow focuses on the classification of three main phases:

* Rock matrix
* Mineral-filled fractures
* Open fractures

The study benchmarks deep learning and conventional image segmentation approaches, including:

* U-Net
* Watershed segmentation
* Multi-Otsu thresholding

The results show that the U-Net-based deep learning approach provides strong performance for multiphase segmentation of naturally fractured media, outperforming the conventional methods evaluated in the study.

## Key Results

In the published study, the U-Net model achieved:

* Intersection over Union: 94.9%
* Dice Score: 97.0%
* Recall: 97.5%

These results demonstrate the capability of deep learning-based segmentation for handling complex fracture networks and multiphase geological image data.

## Repository Contents

This repository includes Jupyter Notebook implementations for:

* U-Net-based image segmentation
* Watershed segmentation
* Multi-Otsu thresholding
* Image preprocessing and evaluation workflows

The code is intended to support reproducible research and to provide a useful starting point for researchers working on digital rock physics, fractured media characterization, and AI-based geological image analysis.

## Applications

This workflow can support research and development in areas such as:

* Digital rock physics
* Naturally fractured reservoir characterization
* Pore-scale image analysis
* Fracture network analysis
* Multiphase segmentation of geological images
* Porosity and permeability estimation
* AI-assisted rock property prediction
* Benchmarking deep learning and conventional segmentation methods

Researchers may build upon this work by improving model generalization, applying the workflow to new rock types, extending the approach to 3D micro-CT datasets, or integrating segmentation outputs with physics-based and data-driven property prediction models.

## Environment

The original development environment used GPU acceleration with CUDA support. Main Python packages include:

* PyTorch
* TorchVision
* TorchMetrics
* segmentation-models-pytorch
* scikit-learn
* scikit-image
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Pillow
* tqdm

Please refer to `requirements.txt` for the package versions used in the repository.

## Usage Notice

This repository is provided for academic and research purposes **ONLY**. You are welcome to use, modify, and build upon the provided code for your own research work.

If you use this repository, please cite the related paper and reference this GitHub repository.

## Citation

```bibtex
@article{Tabrizipour2026MultiphaseSegmentation,
  title   = {Multiphase Image Segmentation of Naturally Fractured Media: Benchmarking Deep Learning and Conventional Approaches},
  author  = {Tabrizipour, Behrad and Sadeghnejad, Saeid and Hajipour, Mastaneh and Schäfer, Thorsten},
  journal = {InterPore Journal},
  volume  = {3},
  number  = {1},
  year    = {2026},
  doi     = {10.69631/j6zv1891}
}
```

## Paper

DOI: https://doi.org/10.69631/j6zv1891

## Contact

For research collaboration or questions related to this work, please contact:

[behrad.tabrizipour@srbiau.ac.ir](mailto:behrad.tabrizipour@srbiau.ac.ir)
[behradtp@gmail.com](mailto:behradtp@gmail.com)

