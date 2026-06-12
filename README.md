# Mexican_Spanish_Datatest2


# 🇲🇽 Mexican Spanish Sentiment Dataset v2

## 📌 Overview

This project contains a labeled dataset of Mexican Spanish sentences designed for sentiment analysis tasks in Natural Language Processing (NLP).

The dataset includes real-world informal expressions commonly used in Mexico, including slang, social media language, and conversational phrases.

It is intended for training and evaluating machine learning models for sentiment classification in Spanish (Mexico variant).

---

## 🎯 Objective

The goal of this dataset is to support NLP research and development focused on:

- Sentiment analysis in Mexican Spanish
- Understanding informal language and slang
- Improving model performance on Latin American Spanish variations
- Training lightweight or experimental ML models

---

## 🧠 Dataset Structure

Each entry contains:

| Column | Description |
|--------|-------------|
| id | Unique identifier |
| text | Sentence in Mexican Spanish |
| label | Sentiment class (positive, negative, neutral) |
| source | Origin of the text (manual, twitter, tiktok, review) |
| emotion_intensity | Strength of emotion (low, medium, high) |

---

## 📊 Labels

- **positive** → Expressions with positive sentiment or emotion
- **negative** → Expressions with negative sentiment or emotion
- **neutral** → Objective or emotionally neutral expressions

---

## 🔥 Emotion Intensity

- **low** → Mild emotional tone
- **medium** → Moderate emotional tone
- **high** → Strong emotional expression

---

## 📁 Example Data

```csv
id,text,label,source,emotion_intensity
1,"No manches, qué padre estuvo eso",positive,tiktok,high
2,"Me dio un buen de coraje lo que pasó",negative,twitter,high
3,"Está bien, nada especial la verdad",neutral,manual,low
