Multimodal Emotion & Stress Detection using Deep Learning
===========================================================
Overview
---------
This project focuses on detecting emotions and stress in children’s conversations using a multimodal deep learning approach combining audio and text data.

The system leverages advanced models such as CNN, BiLSTM, and Transformer-based architectures to improve emotion classification accuracy.

Key Features
--------------
-Audio-based emotion recognition (RAVDESS, CBESD)
-Text-based emotion classification (Govi dataset)

Deep learning models:
-CNN (feature extraction)
-BiLSTM (sequence modeling)
-BERT / DistilBERT (text understanding)

Multimodal fusion (audio + text)

Evaluation metrics:
-------------------
Accuracy
Precision, Recall, F1-score
ROC-AUC

Visualization:
--------------
Confusion Matrix
Emotion distribution plots
Word clouds

Datasets Used
--------------
RAVDESS – Emotional speech dataset
CBESD (English subset) – Child bilingual emotion speech dataset
Govi NLP Dataset – Text-based emotion dataset

Methodology
--------------
1. Audio Processing
Feature extraction using:
MFCC
Spectrogram
Pitch & energy features
Models:
CNN
BiLSTM

2. Text Processing
Text cleaning & normalization
Tokenization using Transformer tokenizer
Models:
BERT / DistilBERT

3. Multimodal Fusion
Combine audio + text features
Fusion strategies:
Early fusion
Late fusion
Attention-based fusion

Results Summary
----------------
Audio models: Moderate performance due to overlapping acoustic patterns
Text models: High performance using contextual understanding
Transformer models (DistilBERT): Best accuracy among tested models
Multimodal approach: Potential for highest accuracy

Installation
# Clone the repository
git clone https://github.com/SanghamitraPanda/EMOTION-AND-STRESS-DETECTION-USING-DEEP-LEARNING-FROM-CHILDREN-S-CONVERSATION.git

Key Findings
----------------
Audio features alone are insufficient for fine-grained emotion detection
Text-based models significantly improve classification accuracy
Transformer architectures outperform traditional ML models
Multimodal fusion enhances robustness

Limitations
----------------
Class imbalance in datasets
Derived stress labels (CBESD)
Computational constraints (limited use of advanced models like wav2vec)

Future Work
----------------
Implement full multimodal fusion with attention mechanisms
Use larger datasets for better generalization
Apply explainable AI (SHAP, LIME)
Real-time stress detection system

References
----------------
RAVDESS Dataset
CBESD Dataset
Govi NLP Emotion Dataset
Transformer models (BERT, DistilBERT)

Author
----------------
Sanghamitra Panda
Data & AI Professional