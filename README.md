# Awesome 3D Generation

This repo collects papers connected with 3D generation.

## Table of Contents
- [Image-to-3D](#image-to-3d)
- [Text-to-3D](#text-to-3d)
- [Image-to-3D and Text-to-3D](#image-to-3d-and-text-to-3d)
- [Human Generation](#human-generation)

## Image to 3D
| Paper | Release | Code / Demo | Testing Specs | Testing Results |
| :---------------------------------------------------------- | :-------: | :-------: | :-----------: | :-----------: |
| [Magic-Boost: Boost 3D Generation with Mutli-View Conditioned Diffusion](https://arxiv.org/abs/2404.06429) | 04.2024 | [Code (empty) ](https://github.com/magic-research/magic-boost) <br> Planned release date: 05.2024 | GenTime: 15 min<br>GPU: A100 (40GB) | <img src="assets/MagicBoost/armor_final.gif" width="120" /> |
| [Diffusion Time-step Curriculum for One Image to 3D Generation (CVPR 2024)](https://arxiv.org/pdf/2404.04562) | 04.2024 | [Code (empty) ](https://github.com/yxymessi/DTC123) <br> Planned release date: 06.2024 | GenTime: 25 min<br>GPU: A100 (40GB) | <img src="assets/DTC123/photo.jpeg" width="120" /> |
| [Compress3D: a Compressed Latent Space for 3D Generation from a Single Image](https://arxiv.org/pdf/2403.13524) | 03.2024 | No code | GenTime: 7 sec<br>GPU: A100 (40GB) | <img src="assets/Compress3D/concat_comparison_caption.gif" width="120" /> |
| [OpenLRM: Open-Source Large Reconstruction Models](https://arxiv.org/abs/2311.04400) | 11.2023 | [Code](https://github.com/3DTopia/OpenLRM)<br>[Colab](https://colab.research.google.com/drive/15uq46FFdzEXUfOuR-TPEpZzfgrb2q-GO?usp=sharing)<br>[HF Demo](https://huggingface.co/spaces/zxhezexin/OpenLRM) | GenTime: 1 min<br>GPU: 15Gb (base model), >40Gb (large model) | <img src="assets/OpenLRM/mickey-mouse.gif" width="120" /> |


## Text to 3D


## Image to 3D and Text to 3D
| Paper | Release | Code / Demo | Testing Specs | Testing Results |
| :---------------------------------------------------------- | :-------: | :-------: | :-----------: | :-----------: |
| [GRM: Large Gaussian Reconstruction Model for Efficient 3D Reconstruction and Generation](https://arxiv.org/abs/2403.14621) | 03.2024 | [Code (empty)](https://github.com/justimyhxu/GRM?tab=readme-ov-file) <br> [HF Demo](https://huggingface.co/spaces/GRM-demo/GRM) | GenTime: 2 min  | <img src="assets/GRM/gs.gif" width="120" />  |


## Human Generation
| Paper | Release | Code / Demo | Testing Specs | Testing Results |
| :---------------------------------------------------------- | :-------: | :-------: | :-----------: | :-----------: |
| [Portrait3D: Text-Guided High-Quality 3D Portrait Generation Using Pyramid Representation and GANs Prior](https://arxiv.org/pdf/2404.10394) | 04.2024 | [Code](https://github.com/oneThousand1000/Portrait3D) | GenTime: 30 min<br>GPU: 24GB<br>No mesh (only .mrc file) | <img src="assets/Portrait3D/photo.jpeg" width="120" /> |