# Emotion Training

Creating a emotion detecting model trained on team members' own emotion expressed facial photos


## Data Preparation

We use the **FER-2013** dataset from Kaggle:  
https://www.kaggle.com/datasets/msambare/fer2013


## Baseline Model: 3-Class Facial Expression Classifier

*Notebook:* `기본모델_유형구분_전시회용.ipynb`  

> Get the general emotion detection model by training all the photos of the members and classify the input photo into one of the 3 categories `HAPPY`, `SAD`, `ANGRY` according to project-defined criteria


## Emotion-Specific Models - `HAPPY`, `SAD`, `ANGRY`

*Notebooks:* `모델1_happy.ipynb`, `모델2_sad.ipynb`, `모델3_angry.ipynb`  

> Get the emotion-specific emotion detection models by training the photos of the members that meet the project-defined criteria for each emotion


## Expressiveness Model: Detecting How Strongly Emotions Are Expressed

*Notebook:* `개별모델_유형구분_전시회용.ipynb`  

> Using emotion-specific models, classify the subject in the input photos as “expressive” (high expressiveness) or “emotion-concealing” (low expressiveness)
