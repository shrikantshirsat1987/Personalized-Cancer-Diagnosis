# Personalized-Cancer-Diagnosis

## 1. Description

A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.

But this is only partially happening due to the huge amount of manual work still required. Memorial Sloan Kettering Cancer Center (MSKCC) launched this competition, accepted by the NIPS 2017 Competition Track,  because we need your help to take personalized medicine to its full potential.

Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). 

Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.

For this competition MSKCC is making available an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations.

We need your help to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.

Context:
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198462

## 1.1 Business Problem

## Problem statement :
Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

## 1.2. Real-world/Business objectives and constraints.
+  No low-latency requirement.
+  Interpretability is important.
+  Errors can be very costly.
+  Probability of a data-point belonging to each class is needed.

## 2. Machine Learning Problem 

## 2.1. Type of Machine Learning Problem
        There are nine different classes a genetic mutation can be classified into => Multi class classification problem

## 2.2. Performance Metric

Metric(s): 

+  Multi class log-loss
+  Confusion matrix

## 2.3. Machine Learing Objectives and Constraints

Objective: Predict the probability of each data-point belonging to each of the nine classes.

## Constraints:

+  Interpretability  

+  Class probabilities are needed.  

+  Penalize the errors in class probabilites => Metric is Log-loss.

+  No Latency constraints.

## Acknowledgments
+  Applied AI Course
