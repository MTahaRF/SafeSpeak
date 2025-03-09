# SafeSpeak

SafeSpeak is a prototype AI-powered cyberbullying detection system that classifies online messages into three categories: **normal**, **offensive**, or **hatespeech**. It leverages Google's **Gemini** model and fine-tunes it for enhanced classification accuracy.

## Features
- **Multi-label Classification**: Detects whether a message is normal, offensive, or hate speech.
- **Fine-tuned Gemini Model**: Custom-trained on the HateXplain dataset for improved accuracy.
- **Automated Data Processing**: Downloads, processes, and visualizes the dataset for analysis.
- **Real-time Predictions**: Classifies messages dynamically using the fine-tuned model.

## Dataset
The dataset used for training is **HateXplain**, available on Kaggle:
[Cyber Bullying Data for Multi-Label Classification](https://www.kaggle.com/datasets/sayankr007/cyber-bullying-data-for-multi-label-classification)

The model will classify a given text as **normal**, **offensive**, or **hatespeech**.

## Model Fine-Tuning
SafeSpeak fine-tunes **Gemini 1.5 Flash** using the HateXplain dataset. It trains for **2 epochs** with a **batch size of 16** and dynamically monitors the training process.

### Example Classification
**Input:**
> "I hate you. You should disappear."

**Output:**
> **Classification: hatespeech**

## Future Enhancements
- Deploy SafeSpeak as an API for real-time moderation.
- Extend classification to other forms of toxic content.
- Optimize for multilingual cyberbullying detection.

## Disclaimer
SafeSpeak is a prototype and may not be 100% accurate. Further fine-tuning and evaluation are required before production use.

---
🚀 Developed as part of an AI initiative to promote safer online spaces.

