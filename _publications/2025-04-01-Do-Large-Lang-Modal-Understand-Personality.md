---
title: "Do Large Language Models (LLMs) Really Understand Personality? A Test of Embeddings vs. Zero-Shot (Preprint)"
collection: publications
category: manuscripts
permalink: /publication/2025-04-01-Do-Large-Lang-Modal-Understand-Personality
excerpt: 'User Demographics are often hidden in social media data due to privacy concerns. However, demographic information on Substance Use can provide valuable insights, allowing Public Health policymakers to focus on specific cohorts and develop efficient prevention strategies, especially during global crises like COVID-19.'
date: 2025-04-01
venue: 'J Med Internet Res 2025'
slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
citation: 'Maharjan J Do Large Language Models (LLMs) Really Understand Personality? A Test of Embeddings vs. Zero-Shot JMIR Preprints. 01/04/2025:75347'
---

### Objective:

This study evaluates LLM embeddings for personality trait prediction through four key analyses: (1) performance comparison with zero-shot methods on PANDORA Reddit data, (2) psychometric validation and correlation with LIWC and emotion features, (3) benchmarking against traditional feature engineering approaches, and (4) assessment of model size effects (OpenAI vs BERT vs. RoBERTa). We aim to establish LLM embeddings as a psychometrically valid and efficient alternative for personality assessment.

### Methods:

We conducted a multi-stage analysis using 1 million Reddit posts from the PANDORA Big Five Personality dataset. First, we generated text embeddings using three LLM architectures (RoBERTa, BERT, and OpenAI) and trained a custom BiLSTM model for personality prediction. We compared this approach against zero-shot inference using prompt-based methods. Second, we extracted psycholinguistic features (LIWC categories and NRC emotions) and performed feature engineering to evaluate potential performance enhancements. Third, we assessed the psychometric validity of LLM embeddings through: (1) reliability testing using Cronbach's alpha, and (2) convergent validity analysis by examining correlations between embeddings and established linguistic markers. For the latter, we applied Lasso regression for feature selection followed by Pearson correlation analysis between significant linguistic features and embedding dimensions for each personality trait.

### Results:

Large Language Model (LLM) embeddings trained using simple deep learning techniques significantly outperform zero-shot approaches across all personality traits. Psychometric validation tests indicate moderate reliability, with an average Cronbach’s alpha of 0.63. Correlation analyses reveal strong associations between LLM embeddings and linguistic/emotional markers: Openness correlates highly with Social (0.53), Conscientiousness with Linguistic (0.46), Extraversion with Social (0.41), Agreeableness with Pronoun usage (0.40), and Neuroticism with Politics-related text (0.63). Advanced feature engineering did not improve model performance, suggesting that LLM embeddings inherently capture key linguistic features. Additionally, model size impacts efficacy, with OpenAI-based models outperforming RoBERTa. These findings highlight the potential of LLM embeddings in personality trait analysis.

### Conclusions:

Our findings demonstrate that LLM embeddings offer a robust alternative to zero-shot methods in personality trait analysis, capturing key linguistic patterns without requiring extensive feature engineering. The correlation with established psycholinguistic markers and the influence of model size underscores their potential for scalable and efficient personality assessment. Further research should explore fine-tuning strategies to enhance psychometric validity.