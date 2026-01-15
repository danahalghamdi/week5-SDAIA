# week5-SDAIA
# Arabic BERT Text Classifier (Fruit vs Vegetable)

This project demonstrates fine-tuning a BERT-based model on Arabic text for a classification task.

## Overview
The original dataset consists of recipe titles labeled as either **Fruit** or **Vegetable**.  
To adapt the task to Arabic, a small subset of the dataset was partially translated into Arabic and used to fine-tune an **Arabic BERT (AraBERT)** model.

## Objective
- Perform the same classification exercise on Arabic data.
- Fine-tune a BERT model to work as a text classifier on Arabic inputs.

## Method
- Use the original recipe dataset.
- Translate a subset of recipe titles into Arabic.
- Fine-tune an Arabic BERT model for binary classification.
- Evaluate the model on unseen Arabic recipe titles.

## Model
- **AraBERT (bert-base-arabertv2)**
- Task: Binary text classification (Fruit vs Vegetable)

## Open in Colab
https://colab.research.google.com/github/danahalghamdi/week5-SDAIA/blob/main/C2_M3_Lab_4_finetuned_text_classifier_AR_improved.ipynb

## Results
The fine-tuned model is able to distinguish between fruit-based and vegetable-based recipes written in Arabic, demonstrating successful adaptation to Arabic text.

## Notes
This work focuses on demonstrating the methodology rather than achieving maximum accuracy. Only a subset of the dataset was translated to satisfy the exercise requirements.
