# Brain tumor repository

Brain tumor classification on MRI scans with transfer learning.

- Dataset on Kaggle: https://www.kaggle.com/datasets/tombackert/brain-tumor-mri-data
- Notebook: `brain-tumor-mri-classification-xception.ipynb`

## Objectives

- Learn about brain tumors and medical image classification
- Try out different models for tumor classification
- Gain new insights on tumor classification

## About the dataset

`brain-tumor-mri-dataset/` contains 7,153 brain MRI images in four classes, combined from three public datasets.

| Class | Folder | Images |
|---|---|---|
| Glioma | `glioma/` | 1,621 |
| Meningioma | `meningioma/` | 1,775 |
| No tumor | `notumor/` | 2,000 |
| Pituitary tumor | `pituitary/` | 1,757 |

One folder per class, no predefined train/test split.

## Sources and licenses

The dataset is a compilation. Each image remains under the license of its original source; please credit and cite the original authors.

1. **brain tumor dataset** – Jun Cheng, figshare, **CC BY 4.0**
   https://doi.org/10.6084/m9.figshare.1512427
   Cheng J. et al. (2015): Enhanced Performance of Brain Tumor Classification via Tumor Region Augmentation and Partition. PLoS ONE 10(10): e0140381.
2. **Brain Tumor Classification (MRI)** – Sartaj Bhuvaji et al., Kaggle, **MIT**
   https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri
3. **Br35H :: Brain Tumor Detection 2020** – Ahmed Hamada, Kaggle, **Data files © Original Authors**
   https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection

Br35H is published without an explicit license; rights to these images remain with the original authors.

A curated, expert-annotated derivative of the same three sources with segmentation masks is **BRISC 2025** (CC BY 4.0): https://www.kaggle.com/datasets/briscdataset/brisc2025

## Limitations

- Images come from different sources with differing resolution, contrast and preprocessing.
- Duplicates across sources are possible.
- Labels are taken from the original sources and were not re-verified.
- Classification only: no segmentation masks included.
- For research and education only, not for clinical use.
