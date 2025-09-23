# dementianet-whisper-xai
Speech analysis on DementiaNet dataset using Whisper ASR and Explainable AI to study dementia vs. non-dementia recordings.

This project applies OpenAI’s Whisper model to the DementiaNet dataset (speech recordings of people with and without dementia) to generate transcriptions and extract features. Explainable AI methods are used to interpret model predictions and highlight linguistic and acoustic markers of dementia. 

# DementiaNet Whisper XAI

This project applies **OpenAI Whisper** to the [DementiaNet dataset](https://github.com/shreyasgite/dementianet), which contains speech recordings of people with and without dementia.  
We use **Explainable AI (XAI) methods** such as SHAP and LIME to interpret model predictions and explore linguistic and acoustic markers relevant to dementia detection.

---

## Project Description
- **Dataset**: DementiaNet (recordings of dementia vs. non-dementia participants)  
- **Model**: Whisper (Automatic Speech Recognition, ASR)  
- **XAI**: SHAP, LIME for interpretability of ASR features and predictions  
- **Goal**: To analyze speech patterns and demonstrate how XAI can provide insights into dementia vs. non-dementia recordings.  

---

## Data Access
The dataset is **not included** in this repository.  
To reproduce the results:

1. Clone or visit the original [DementiaNet repository](https://github.com/shreyasgite/dementianet).  
2. Download the dataset from the Google Drive link provided there.  
3. Place the dataset in your own Google Drive, e.g. under:
