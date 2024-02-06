# Twitter Sentiment Analysis

2024 Senior Portfolio Project. A Twitter Sentiment Analysis application that includes a research comparison between a fine-tuned DistilBERT model and a six-layer CNN made from scratch for sentiment analysis. The final application will provide an option to select between the two models and will have the ability to gather live tweets using Twitter's API. Currently in progress with a completion date of April 2024.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Models](#models)
- [Live Tweet Gathering](#live-tweet-gathering)
- [Progress](#progress)

## Introduction
In the rapidly evolving digital age, the vast amounts of data generated online, such as social media posts, blogs, and reviews, offer invaluable insights into public sentiment. Natural Language Processing (NLP) has emerged as a key technology enabling the analysis of this data at scale, providing a means to process and understand the sentiments expressed in large datasets without manual intervention. Sentiment analysis, a technique within NLP, tags text according to its sentiment polarity, facilitating real-time, data-driven decision-making for individuals, companies, and organizations.

## Project Overview

This research project focuses on applying sentiment analysis to user-generated data to help decode public sentiment efficiently. By leveraging advanced NLP techniques, the project aims to process large datasets in real-time, allowing for the rapid understanding of public sentiment. This capability is vital for applications such as social media monitoring, survey feedback analysis, and customer support.

## Models

### Six-layer Convolutional Neural Network (CNN)

- **Feature Extraction:** Utilizes convolutional and pooling layers to learn word or phrase patterns indicative of sentiment.
- **Complex Pattern Learning:** Stacks multiple layers to understand higher-level linguistics and classify data more effectively.
- **Context Understanding:** Captures local dependencies between words or n-grams to grasp the context, essential for sentiment analysis.
- **Efficiency:** Employs a consistent set of weights across inputs to reduce parameter count, enhancing dataset processing efficiency.

### Fine-tuned DistilBERT Model

- **Advanced NLP:** Leverages the distilled version of BERT, a large transformer model known for self-attention mechanisms, positional embeddings, and multihead attention, to achieve high accuracy.
- **Transfer Learning:** Enables fine-tuning for specific tasks, such as Twitter sentiment analysis, improving model performance on specialized datasets.
- **Comparative Analysis:** Assesses the performance of DistilBERT against CNN in terms of efficiency, robustness, generalization, and error rates to evaluate practical deployment considerations like latency and scalability.

## Live Tweet Gathering

This section will describe the methodology for collecting real-time Twitter data for analysis. [Details to be added]

## Progress

Currently this project is in the preliminary stages with initial research fully complete. The project is now moving into phase two, which includes the creation/training of each model.
