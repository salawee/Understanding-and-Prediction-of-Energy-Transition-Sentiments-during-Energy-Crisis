# ⚡ Understanding and Prediction of Energy Transition Sentiments during Energy Crisis ⚡

## 🔍 Overview

This repository presents a comprehensive analysis of public sentiment toward the energy transition from traditional sources, such as oil and gas, to hydrogen energy, specifically during the COVID-19 pandemic. Using Twitter data, we employ Natural Language Processing (NLP) and machine learning techniques to understand how public perceptions around hydrogen energy have evolved in a time of crisis.

The core focus of this project is to support stakeholders, policymakers, and energy companies in making informed decisions regarding renewable energy adoption, with hydrogen positioned as a sustainable and viable alternative. This study introduces a specialized NLP model called Hydrogen BERT, which is tailored to analyze the nuanced conversations regarding hydrogen energy, enabling deeper insight into public sentiment.

This project is crucial for assessing the public perception of hydrogen as a solution to climate change challenges, balancing economic, technological, and infrastructural barriers that have impacted its widespread adoption.

## 📑 Table of Contents
- [Introduction](#introduction)
- [Why Hydrogen Energy](#why-hydrogen-energy)
- [Methodology](#methodology)
  - [Data Collection and Processing](#data-collection-and-processing)
  - [Hydrogen BERT Model](#hydrogen-bert-model)
  - [Machine Learning Models for Sentiment Analysis](#machine-learning-models-for-sentiment-analysis)
- [Results](#results)
  - [Sentiment Analysis by Demographics](#sentiment-analysis-by-demographics)
  - [Key Findings](#key-findings)
- [Discussion](#discussion)
- [Future Research Opportunities](#future-research-opportunities)
- [Contributions](#contributions)
- [Citation](#citation)

## 📘 Introduction

The COVID-19 pandemic created significant shifts in public opinion and priorities regarding energy usage, with a strong focus on renewable alternatives like hydrogen. This project aims to understand and predict these shifts in public sentiment by analyzing Twitter data during the pandemic using advanced NLP models.

Hydrogen energy, as a clean and sustainable option, offers a potential solution to climate change challenges. However, its adoption is affected by technological, economic, and infrastructural barriers, alongside fluctuating public perceptions influenced by the pandemic. By accurately gauging public sentiment, stakeholders can adapt their policies and investments, ensuring better market adoption and success for hydrogen technologies.

**🖼️ [Image Placeholder: Chart showing overall tweet sentiment trends]**

## 💧 Why Hydrogen Energy

Hydrogen energy presents significant advantages as a clean and versatile energy source:

- **Storage**: Hydrogen can be stored for extended periods, addressing the intermittency issues faced by other renewable sources like wind and solar.
- **Zero Emissions**: Hydrogen energy produces no greenhouse gases when used, making it a key candidate for mitigating climate change.
- **Versatility**: Hydrogen has broad applications in industries, transportation, and electricity generation, which makes it an attractive solution for a sustainable energy transition.

Given the context of climate change, the adoption of hydrogen energy is essential. Hydrogen is uniquely positioned to address pressing environmental issues, offering a path to a sustainable and equitable energy future.

## 🛠️ Methodology

### 📊 Data Collection and Processing

For this analysis, we collected tweets via the Twitter Academic API during the peak of the COVID-19 pandemic. The data preprocessing steps involved:

- **Removal of Stop Words**: Eliminated common words (e.g., "and", "the", "is") to enhance analysis.
- **Lowercasing and Special Character Removal**: Text was converted to lowercase, and special characters were removed to ensure uniformity.
- **Stemming and Lemmatization**: Reduced words to their base forms for consistency.
- **Annotation**: Labeled the data to prepare it for supervised learning models.

The data underwent advanced Natural Language Processing to ensure that only relevant features were included for analysis, making the dataset ready for sentiment prediction using various models.

### 🤖 Hydrogen BERT Model

The **Hydrogen BERT** model was developed to accurately capture the nuances in discussions about hydrogen energy during the pandemic. It builds upon the BERT (Bidirectional Encoder Representations from Transformers) architecture but is specifically trained on hydrogen-related conversations, giving it domain-specific insights.

The model:
- **Captures domain-specific terminology** related to energy transition.
- **Understands bidirectional context**, allowing it to determine the sentiment by considering words both before and after a given phrase.
- **Enables continuous learning**, meaning it can be updated to adapt to ongoing changes in public opinion.

![image](https://github.com/user-attachments/assets/72c5bb97-5a37-496e-908f-28d3a458b056)


### 🔄 Machine Learning Models for Sentiment Analysis

In addition to Hydrogen BERT, we employed several traditional machine learning models for comparative analysis:

- **Support Vector Machine (SVM)**: Utilized for its strength in classification accuracy.
- **Random Forest**: Provided insights into sentiment distribution, particularly for complex, non-linear trends.
- **Logistic Regression and Decision Trees**: Benchmarked against BERT to measure effectiveness across accuracy, precision, and recall.

Feature extraction techniques, such as **TF-IDF** (Term Frequency-Inverse Document Frequency), **Word2Vec**, and **Count Vectorizer**, were used to convert the textual data into numerical representations suitable for modeling.

**🖼️ [Image Placeholder: Performance metrics of different machine learning models]**

## 🎯 Results

### 📊 Sentiment Analysis by Demographics

The analysis provided insights into how different demographics perceive hydrogen energy:

- **Gender Analysis**: 
  - **Females**: Predominantly expressed neutral sentiments.
  - **Males**: Showed higher positivity regarding hydrogen energy.
  - **Others**: Representing entities like media outlets, generally leaned towards neutral sentiment.

- **Race Analysis**: Caucasians were more optimistic about the hydrogen transition, while sentiments among other groups were more varied.

- **Socio-Economic Analysis**:
  - Individuals with higher **median incomes** tended to have more positive views.
  - **Higher educational levels** correlated with more nuanced (neutral) opinions, indicating a more critical evaluation of hydrogen energy.
  - **Employment status** played a role, with higher employment rates being linked to positive sentiments.

![image](https://github.com/user-attachments/assets/df788137-e232-4625-994d-750dacd8708f)

### 🔍 Key Findings

1. **Public Interest in Hydrogen Energy**: Sentiments during the pandemic showed significant interest in hydrogen energy, with optimism about its potential role in combating climate change.
2. **Hydrogen BERT Model Performance**: The Hydrogen BERT model successfully captured domain-specific discussions, performing better than traditional sentiment analysis models.
3. **Gender and Socio-Economic Influences**: Positive sentiments were higher among males, high-income individuals, and people from metropolitan areas, highlighting the socio-economic factors influencing attitudes toward hydrogen.
4. **Geographical Insights**: The **U.S.** led in terms of tweet volume, indicating greater interest or social media presence, followed by **India** and **France**. Within the U.S., metropolitan areas like **Oklahoma City** showed higher tweet density, pointing to urban interest in hydrogen technology.

![image](https://github.com/user-attachments/assets/5342ab84-0953-4242-93e9-d622518b712f)
![image](https://github.com/user-attachments/assets/79e7dbc7-bf00-49c5-aeff-32d313bd9f71)

## 💭 Discussion

The results of this project underscore the power of combining machine learning and NLP techniques to analyze energy transition sentiments. By leveraging Hydrogen BERT, we were able to extract detailed sentiment patterns that provide valuable insights for stakeholders and policymakers.

The findings highlight how different demographic and socio-economic factors shape public sentiment about hydrogen energy. Positive sentiments are primarily driven by optimism around its clean energy potential, while skepticism often stems from economic and technological barriers that hinder its mass adoption.

Moving forward, these models can be continuously trained with newer data to reflect evolving public opinion and ensure the findings are relevant for decision-makers in the energy sector.

## 🌱 Future Research Opportunities

- **Integration of Economic and Policy Factors**: Incorporate additional data on global economic conditions and government policies to enhance sentiment analysis.
- **Geospatial Sentiment Mapping**: Analyze public sentiment across different regions more thoroughly to understand regional variations in hydrogen energy perception.
- **Broader Social Media Data**: Extend analysis to include data from platforms like LinkedIn and Facebook to capture a broader spectrum of public opinion.

## 🤝 Contributions

We welcome contributions from developers, data scientists, and those passionate about energy sustainability. Contributions could include improving the Hydrogen BERT model, adding new features, or extending the analysis to cover different periods or renewable energy sources. Let's collaborate to advance renewable energy adoption and public engagement in sustainable energy solutions.

## 📚 Citation

Please cite this work as follows:

Khondhaker Al Momin, Nayem Ahmed, Syed Ishmam Alawee, Ali Dashti Rahmatabadi, "Understanding and Prediction of Energy Transition Sentiments during Energy Crisis: An Analysis of Twitter Data." 2024.
