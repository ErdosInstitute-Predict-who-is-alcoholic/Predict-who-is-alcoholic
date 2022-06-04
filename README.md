# Classification of Alcoholic EEG Signals

## may22-themis Team:
Azeezat Azeez and Miriam Sierra

## Background: Electroencephalography
The EEG(Electroencephalography) is a non-invasive neuroimaging technique used  to record electrical activity from the scalp, representative of real time neural activity at high temporal resolution.
In Clinical setting EEG is primary used to diagnose Epilepsy

## Project Description: Predict who is an Alcoholic?
- Data: Open-source EEG data from the UCI Machine Learning Repository 
	https://archive.ics.uci.edu/ml/datasets/EEG+Database
	
- Description: This data arises from a large study to examine EEG correlates of genetic predisposition to alcoholism.
	It contains measurements from 64 electrodes placed on subject's scalps which were sampled at 256 Hz (3.9-msec epoch) for 1 second.
	
- Subjects: Two Groups: Alcoholic  & Control 
	
- Data Sets: 
	Training:  20 unique patients (10 control/10 alcoholic) 30 trials per patient


## Motivation: Preventive Care & Improved Social Welfare
- 14M  people suffer from alcohol use disorder in the US 
- Current method of diagnosis is largely qualitative (self reports) which can introduce bias 
- The quantitative  ability to diagnose discover high risk individuals based on biomarkers of EEG data has real world benefits:

Medical: Identify  high risk and vulnerable populations→ Preventive Care 

Social: Reduce the social burden → Improve Social Welfare 

**Financial: Preventive Care +  Improve Social Welfare**

https://www.niaaa.nih.gov/publications/brochures-and-fact-sheets/alcohol-facts-and-statistics

## Approach: Classification Algorithms  

1. Exploratory Analysis
2. Preprocessing: EEG data using Literature Standard
3. Feature Extraction and Dimension Reduction
4. Machine Learning Algorithms
5. Supervised Learning (Hyperparameter tuning of best classifier)
	- Logistic Regression 
	- Random Forest
	- Support Vector Machine
6. Neural Networks: Classification using deep 1D convolutional neural network

## Summary
The intersection of Data Science and Medical Imaging offer a unique opportunity to create clinical  biomarkers for Patients 
In this Case the potential to offer Preventive Care & Improved Social Welfare for those suffering from Alcohol Use Disorder 
While our current model performance is promising, there is still room to improve the diagnostic utility of the Algorithms. 





