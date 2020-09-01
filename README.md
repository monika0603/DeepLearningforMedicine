# Welcome to Monika's Machine Learning repository. The intend is to showcase some of my favorite projects:

## Class Imbalance Problem:

I have shown two examples under this category.

-- Example I: This is a very simple case of recommending best airlines based on the number of cancellations it has had in the past.

-- Example II: This is a more complex example of classification type Machine Learning problem simply because there is a severe class imbalance in the data set. I have demonstrated that in the first iteration I am not able to achieve good metrics for any of the models used. So I completely change the methodology and start from scratch. Second time around, I train my models based on equal number of failure and non-failure cases which renders much improved confusion matrix scores.

## Natural Language Processing:

-- Shows Machine Learning models used for Natural Language Processing (NLP). Here numerous text messages are identified as ham or spam.

-- Analyzed Urdu data set from UC Berkeley repository

## A/B testing:

-- Used Kaggle dataset to show A/B testing using the frequentist and Bayesian method.

## Deep Learning for Medicine

There are two directories in this repository:

  * AI for medical diagnosis
  * AI for medical prognosis
<img src="https://miro.medium.com/max/2652/1*eTkBMyqdg9JodNcG_O4-Kw.jpeg" width="100%">

[Image Source](https://medium.com/stanford-ai-for-healthcare/its-a-no-brainer-deep-learning-for-brain-mr-images-f60116397472)

`AI for medical diagnosis` This is my attempt to learn to find tumors and lesion in the brain using Deep Learning Neural Network. Doctors cannot operate for brain tumor removal unless they know exactly where the tumor is located. It becomes particularly important to know the location of lesions for patients with multiple sclerosis (MS). Knowledge of location helps doctors to track disease progression and to determine if the treatment is working. Magnetic Resonance Imaging (MRI) images can be used to image the brain in 3D but a highly specilized doctor still has to review the resulting images and manually mask the affected volume. This is a difficult and time consuming task. Machine Learning algorithms that could at least partially automate the process would be very valuable. These large datasets are currently lacking but are much needed for medical research. 

[Medium article](https://medium.com/stanford-ai-for-healthcare/its-a-no-brainer-deep-learning-for-brain-mr-images-f60116397472)

[Data Source](https://decathlon-10.grand-challenge.org)

While `AI for medical diagnosis` shows how to deploy Machine Learning models for predicting survival/hazards for patients. Diagram below shows Harrel's C-index that displays accuracy of our models to predict survival rate between any two randomly selected patients based on their risk score. 

<img src="Harrell’s C-Index.png" width="100%">
