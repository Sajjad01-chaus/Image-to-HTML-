# Image-to-HTML Model Development

This project implements a deep learning model that takes an image as input and generates the corresponding HTML code. The model uses the **BLIP (Bootstrapping Language-Image Pre-training)** model for image captioning and HTML token generation. The dataset used for training is the **WebSight** dataset from Hugging Face, which consists of images paired with their corresponding HTML representations.

## Project Overview

The objective of this project is to develop an accurate image-to-HTML model using deep learning techniques. The model is trained using a pre-trained **BLIP model** for image captioning and fine-tuned to generate HTML-like captions for images. The final model can generate HTML code based on image inputs, making it useful for applications such as automated web page generation or image-to-HTML translation.

## Features

- **Image-to-HTML Generation**: The model generates corresponding HTML code from an input image.
- **Model Fine-Tuning**: Uses a pre-trained BLIP model fine-tuned for the task of generating HTML tokens.
- **BLEU Score Evaluation**: The generated HTML is evaluated using BLEU score to ensure accuracy.
- **Google Colab Demonstration**: The trained model can be demonstrated in a Google Colab notebook.

## Installation

To get started with this project, clone the repository and install the required dependencies.

```bash
git clone https://github.com/your-username/image-to-html.git
cd image-to-html
pip install -r requirements.txt
