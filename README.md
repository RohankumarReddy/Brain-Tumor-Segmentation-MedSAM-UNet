# Brain Tumor Segmentation using U-Net and MONAI 🧠

This repository contains code and resources for 3D brain tumor segmentation using the U-Net architecture, powered by the MONAI framework. The model is trained and evaluated on the **BraTS brain tumor dataset**, enabling precise tumor segmentation from MRI scans.

---

## 📁 Dataset

- **Dataset Name**: BraTS (Brain Tumor Segmentation Challenge)
- **Input Modality**: T1, T1Gd, T2, FLAIR (used 3 as input channels)
- **Format**: NIfTI (.nii.gz)
- **Preprocessing**: Done using MONAI transforms (spacing, orientation, normalization, etc.)

---

## 🚀 Model Architecture

- **Base Model**: 3D U-Net
- **Framework**: MONAI (Medical Open Network for AI)
- **Loss Function**: Dice Loss
- **Metric**: Dice Score
- **Inference**: Generates per-patient voxel-wise tumor segmentation masks.

---

## 🧠 Features

- Medical image preprocessing with MONAI
- Training loop with validation and model checkpointing
- Dice score monitoring during validation
- Patient-wise inference with segmentation outputs
- Optional integration with **MedSAM** for prompt-based segmentation


