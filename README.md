Here is a draft for your `README.md` file based on the presentation content:

---

# Suicidal Intent Classification Using Sentiment Analysis

This project focuses on detecting suicidal intent based on sentiment analysis of social media content. Given the increasing rates of mental health issues among adolescents in Indonesia, this system aims to contribute to mental health monitoring by classifying content that indicates suicidal tendencies.

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Dataset](#dataset)
3. [Training Process](#training-process)
4. [Results](#results)
5. [Challenges and Suggestions](#challenges-and-suggestions)
6. [Demo](#demo)

## Problem Statement

- **1 in 3 adolescents** in Indonesia face mental health issues, such as **depression and anxiety**. These issues are often expressed on **social media**, where **85% of adolescents** frequently share their emotions. 
- This project utilizes **sentiment analysis** to detect suicidal intent, aiming to contribute to preventive mental health interventions.

**Sources:**
- Indonesia National Adolescent Mental Health Survey (I-NAMHS) (2022)
- UNICEF (2021)
- BPS (2023)

## Dataset

The dataset includes a balanced set of:
- **Suicidal Posts**: 116,037
- **Non-Suicidal Posts**: 116,037

You can find the dataset at [this link](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health).

## Training Process

- **Data Split**: 
  - Training: 80%
  - Validation: 20%
  
- **Preprocessing**:
  - Convert all text to lowercase.
  - Remove URLs and double spaces.
  
- **Model Used**: 
  - **DistillBERT**, a small, fast, and efficient transformer model.
  
- **Metrics**:
  - **Accuracy** and **F1 Score** were used to evaluate the model's performance.

## Results

- **Validation Accuracy**: 98%
- **Validation F1 Score**: 98%
- **Validation Loss**: 0.0636

## Demo

A demo of the system can be found [here](https://huggingface.co/spaces/pradanaadn/suicidal-intent-detection).

