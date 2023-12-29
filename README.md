# AnimeGAN: Artistic Image Synthesis with Generative Adversarial Networks

<p align="center">
  <img src="GANs_architecter.png" alt="GAN Architecture" width="600"/>
</p>

---

## Overview 🚀

In this project, I created a Generative Adversarial Networks (GANs) model for artistic image synthesis using PyTorch. The model consists of a generator and discriminator trained on the [Anime Face Dataset](https://github.com/bchao1/Anime-Face-Dataset) from either [GitHub](https://github.com/bchao1/Anime-Face-Dataset) or [Kaggle](https://www.kaggle.com/datasets/splcher/animefacedataset). The training involved 100 epochs, and the progress is visualized in a video showcasing generated images for each epoch.

## Table of Contents 📑

- [Project Title](#project-title)
- [Overview](#overview)
- [Table of Contents](#table-of-contents)
- [Demo](#demo)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)

## Demo 🎥

![Generated Images](gans_training100.gif)



> Showcasing generated images for each epoch (from 1 to 100).

Images:
1. Epoch 1 - Initial Noise
   
   ![Epoch 1](images/gans_training_epoch_0.jpg)

3. Epoch 5 - Early Faces with Errors
   
   ![Epoch 5](images/new_gans_training_epoch_5.jpg)

5. Epoch 100 - High-Quality Anime Faces
   
   ![Epoch 100](images/new_gans_training_epoch_100.jpg)

## Dependencies 🛠️


[![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white&logoSize=2)](#)   [![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white&logoSize=2)](#)   [![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white&logoSize=2)](#)   [![NumPy](https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white&logoSize=2)](#)   [![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white&logoSize=2)](#)   [![Pillow](https://img.shields.io/badge/-Pillow-8CAAE6?style=for-the-badge&logo=python&logoColor=white&logoSize=2)](#)



## Installation 💻

```bash
# Install dependencies
pip install python PyTorch opendatasets numpy matplotlib Pillow opencv-python
```

## Usage 🚀

To use and train the model:

1. Open the notebook in [Google Colab]([https://colab.research.google.com/your-notebook](https://colab.research.google.com/github/mouraffa/Generative-Adversarial-Networks-GANs-for-Anime-Image-Generation/blob/main/Generative_Adversarial_Networks_(GANs)_for_Anime_Image_Generation.ipynb)).
2. Change the runtime to GPU for faster training.
3. Modify the number of epochs in the notebook according to your preference.
4. Run the notebook.

For local machine usage, configure GPUs following the instructions in the first cell of the notebook.
