# Simulation and real data analysis of methods identifying and processing covariate shift

This repository stores all the codes involved in Claire Lou's undergraduate thesis, ‘Definition, Identification, Detection and Correction of Covariate Shift Problem in Transfer learning’. It consists of three parts: the simulation code, the real data analysis code and the real data analysis case datasets, which corresponds to the content of Chapter 5 of the thesis. As errors and omissions are inevitable, all users are sincerely urged to take note of this and the author kindly welcome comments for correction.

## Part 1: Simulation of covariate shift cases with processing methods  (all R)

This section contains full R code of two simulation cases, which exactly corresponds to Section 5.1 and 5.2 of the thesis.

- Case 1.1 (R)： Covariate shift simulation based on a regression task, consisting of a linear regression model applied to predict missing labels for one-dimensional instance-labelled pairs of data.
  
- Case 1.2 (R)： Covariate shift simulation based on a classification task, consisting of a classic SVM classification model applied to predict category labels for two-dimensional instance-labelled pairs of data.

## Part 2: Real data analysis of covariate shift cases with processing methods  (R & Python)
This section contains full R & Python code of two real data analysis cases, which exactly corresponds to Section 5.3 of the thesis. 

- Case 2.1 (R):  Risk prediction of discharge status in patients with sepsis, including all basic machine learning models, sample selection bias-inducing mechanisms, the implementation of two-sample detection method and instance reweighting algorithm.
  
- Case 2.2 (Python):  Covariate shift processing methods of neural networks based on CIFAR data, including assessment of the impact of covariate shift within NNs, testing of the effectiveness of the BN algorithm, and comparison of the effectiveness of NN OOD detection methods.
  
**Note:** Case 2.2 is recommended to be configured for Windows 11 (32 bit) under the implementation of GPU P100 to get desired results.

## Part 3: Real datasets of covariate shift cases in Part 2
This section contains datasets with their appendix, which corresponds to Case 2.1 & Case 2.2 mentioned above in Part 2. 

- Dataset 1: Selected cross-sectional data from the MIMIC-III database containing clinical information on 6273 patients with sepsis

  Source: https://physionet.org/content/mimiciii/1.4/
  
- Dataset 2: CIFAR-10 and CIFAR-100 in the CIFAR series of datasets

  Source: https://www.cs.toronto.edu/~kriz/cifar.html

**Note:** Datasets provided here have been pre-processed, but users are also encouraged to retrieve the data from sources. Same result can be obtained by using processing methods in Part 2 described above.

## Reminder
- All rights to the code in this repository belong to the author Lou, and are for academic use only, and may not be used for any other purposes.

