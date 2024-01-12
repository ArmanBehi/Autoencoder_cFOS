# cFOS_Denoise

This project involves a pretrained denoising model, "Denoised_model," which you should upload to get started in the respective section. To introduce images for processing, please refer to the "Getting Started" section below.

# Autoencoder_cFOS
Autoencoder Convolutional_Neural_Network for reducing Noise_to_signal ratio in Confocal cFOS Images

## Introduction

For a comprehensive scientific description of the project, please refer to the detailed documentation provided in the PDF file titled "cFOS_autoencoder.pdf".


## Installation
To run this code, you need to have the following libraries installed:

    numpy
    torch
    torchsummary
    PIL
    os
    transforms from torchvision
    matplotlib
    IPython
    google.colab

You can install these dependencies using the following command:
```python
bash

pip install numpy torch torchsummary Pillow matplotlib

```

## Getting Started

You have to first Mount your Google drive to import images. Use the following code to mount your Google Drive and access your files:
```python
# Mount Google Drive
from google.colab import drive
drive.mount('/content/drive')

```
In this step, you need to specify the path of your parent folder where your data is stored. The parent folder should include subfolders corresponding to the groups in your experiment.

In the third section, it asks you to provide the modified images. If you really do not have it you could leave it blank.
It also ask you to input the number of epochs.
```
Ensure that your folder structure resembles the following:
```python
YourParentFolder/
├── Group1/
├── Group2/
├── Group3/
# ... (additional groups)
```
Adjust the folder names according to the groups in your experiment.


## Usage

If you just want to use the pretrained model for your current images, use "cFOS_Denoise"
If you want to train the model base on your own data, use "Autoencoder_cFOS".

## Acknowledgments
This project has been done for the lab rotation in the lab "Neural Circuits & Network Dynamics".
https://www.pakanlab.com
