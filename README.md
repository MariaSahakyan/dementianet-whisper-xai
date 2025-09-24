# dementianet-whisper-xai

Speech analysis on the [DementiaNet dataset](https://github.com/shreyasgite/dementianet) using Whisper ASR and Explainable AI to study dementia vs. non-dementia recordings.  

This project applies OpenAI’s Whisper model to the DementiaNet dataset (speech recordings of people with and without dementia) to generate transcriptions and extract features. Explainable AI methods are used to interpret model predictions and highlight linguistic and acoustic markers of dementia.  

---

## DementiaNet Whisper XAI

This repository contains a Colab notebook for analyzing the [DementiaNet dataset](https://github.com/shreyasgite/dementianet), which consists of speech recordings of people with and without dementia.  

The project applies automatic speech recognition (ASR) using **Faster-Whisper** to generate transcriptions. Extracted linguistic and acoustic features are used in a classification pipeline.  
To ensure interpretability, we implement a **custom local explanation method** (inspired by [LIME](https://arxiv.org/pdf/1602.04938)) that highlights which features most strongly influenced predictions for each individual recording.  

---

## Project Description

- **Dataset**: DementiaNet (recordings of dementia vs. non-dementia participants)  
- **Model**: Whisper (Automatic Speech Recognition, ASR)  
- **XAI**: Custom local interpretability of ASR features and predictions  
- **Goal**: To analyze speech patterns and demonstrate how explainability can provide insights into dementia vs. non-dementia recordings.  

---

## Notebooks

- [`XAI_on_ASR_Maria_Sahakyan.ipynb`](XAI_on_ASR_Maria_Sahakyan.ipynb)  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/dementianet-whisper-xai/blob/main/XAI_on_ASR_Maria_Sahakyan.ipynb)  
[View in nbviewer](https://nbviewer.org/github/YOUR_USERNAME/dementianet-whisper-xai/blob/main/XAI_on_ASR_Maria_Sahakyan.ipynb)  

---

## Data Access

The dataset is **not included** in this repository.  
To reproduce the results:

1. Clone or visit the original [DementiaNet repository](https://github.com/shreyasgite/dementianet).  
2. Download the dataset from the Google Drive link provided there.  
3. Place the dataset in your own Google Drive **or create a shortcut to it** in a Google Drive folder.  
   (For example, you can keep the shortcut in the same folder where you also save your output files.)  

---

## Acknowledgment

This work builds on the  [DementiaNet](https://github.com/shreyasgite/dementianet) dataset.
All rights to the dataset remain with the original authors.

