<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Hate speech detection on Twitter
**Laura Sánchez**

*Data Part Time Barcelona Jun 2020*

## Content
- [Project Description](#project)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Results](#results)

<a name="project"></a>

## Project Description

There is an increasing concert about agressive or offensive language on social media and the anonymity in social media makes it even easier for people to offend and insult other people. In this project I am using a dataset from HatEval 2019, with 4450 tweets in Spanish. The goal is to be able to predict our outcome variable, which is a binary variable, HS (HateSpeech), with the highest possible accuracy.



## Dataset

The dataset was extracted form HateEval 2019, and contains the following columns:

- Id: not refering to the Tweet ID

- Text: tweet

- HS: Hate Speech -  Binary variable, 1 if the tweet is hateful, 0 if the tweet is non hateful

- TR and AG: Dropped these columns for simplicity


## Workflow

- Exploratory analysis of reviews
- Data cleaning for Topic Modelling and Word cloud
- LDA
- Tokenization and Pre-processing
- Algorithms


##Organization

The repository contains:
 
- Hate Speech detection analysis notebook
- Original dataset
- Spanish Stopwords file
- Lda.html visualization file


