---
title: 'Zero-shot Text Classification using HuggingFace API'
date: 2024-03-01
permalink: /posts/2024/03/streamlit/
tags:
  - coding
  - ai
  - llm
---

This repository is dedicated for the Zero-Shot Text Classification App, developed as part of the 30-Day Streamlit Challenge, utilizes pre-trained models from the Hugging Face to categorize text into predefined classes without prior training.

Zero-Shot Text Classification App
======

Zero-shot text classification is the task of categorizing text into predefined classes without prior training on those specific classes. Instead, the model leverages its pre-trained knowledge to classify text accurately, even for classes it hasn't seen before.
In this app, you can choose from three base models: Distil-BART, BART-Large, and DeBERTa-v3, provided by the Hugging Face API. Simply input your text, select the desired model, class labels, and key phrases for classification. The app will then request result predictions from the chosen pre-trained model, enabling you to classify text with ease.

You can see more details about the repo in this [link](https://github.com/Alfadhils/Streamlit)