# Whisper-Tiny-German Fine-Tuning Project

## Overview
This mini project focuses on fine-tuning the Whisper-Tiny model by OpenAI using the German dataset from Common Voice 11. Due to computational limitations, I experimented with two variants of the model:

1. **Model V1 (100k Train Data):**
   - Trained for 5 hours with 4000 Steps
   - Achieved a Word Error Rate (WER) of 31% on the test dataset

2. **Model V2 (200k Train Data):**
   - Trained for 10 hours with 8000 Steps
   - Achieved a WER of 32% on the test dataset

Computer Spec = AMD Ryzen 9 5900HS, 8GB of RAM available, RTX 3060 Laptop GPU 6GB of VRAM

## Model Availability
You can find the pre-trained models on Hugging Face:

- [Whisper-Tiny-German V1](https://huggingface.co/LiquAId/whisper-tiny-german-HanNeurAI)
- [Whisper-Tiny-German V2](https://huggingface.co/LiquAId/whisper-tiny-german-V2-HanNeurAI)

## Try Gradio Demo for the ASR and Translation (With gtranslate translator)
You can try the model in this google colab below:
[Demo](https://colab.research.google.com/drive/1no5-2xGblr_NT3aPXFDbHxJ203LVafty?usp=sharing)


*This project is for school project

Created and Trained by Han 2024

Helped by friends in my project group
