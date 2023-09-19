# Udacity Data Scientist Nanodegree Capstone Project

This repository has all the code and report for my Udacity Data Scientist Nanodegree Capstone project.

## Starbucks Capstone Challenge

### 1. Installations
This project was written in Python, using Jupyter Notebook on Anaconda.

### 2. Project Motivation
This project is the Capstone project of my Data Scientist nanodegree with Udacity. I have the option to take part in the Starbucks Capstone Challenge.

For the challenge, Udacity provided simulated data that mimics customer behavior on the Starbucks rewards mobile app.

In this project, I created 3 models for the data on the 3 offer types provided. 

The three offers are:

+ Buy One Get One Free (BOGO)

+ Discount (discount with purchase)

+ Informational (provides information about products).

As a brief summary of my findings:

- The feature importance given by all 3 models were that the tenure of a member is the biggest predictor of the effectiveness of an offer. Further study would be able to indicate what average tenure days would result in an effective BOGO offer.

- My decision to use 3 separate models to predict the effectiveness of each offer type ended up with good accuracy for the 2 of the models (82.83% for BOGO and 87.35% for discount), while slightly less accurate performance for another informational offers (75.3%). However, I would regard 75% as acceptable in a business setting, as for informational offers, there is no cost involved to inform users of a product.

So, an 80% and above accuracy in a business setting would be acceptable to show offers to people, even if the model misclassifies a few, the overall revenue increase might justify the few mistakes.

### 3. File Descriptions

This repo contains 4 files. The report of my project is called `'Starbucks Capstone Challenge.ipynb'`. 

The data used in the project is in the files `portfolio.json`, `profile.json` and `transcript.json`. 

### 4. Licensing, Authors, Acknowledgements, etc.

Data for coding project was provided by Udacity.

## References

### The code on GitHub repo can be found [here](https://github.com/dinhtu44/Data-Scientist-Capstone-Project).

### Medium Blog Post for this project present

The main findings of the project can be found at the Medium Blog post available [here](https://medium.com/@18521589/starbucks-offers-for-sending-smart-ways-71c6949089c)
