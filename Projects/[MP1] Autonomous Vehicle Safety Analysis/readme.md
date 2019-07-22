# Mini Project 1: Autonomous Vehicle Safety Analysis

This project explores failures and disengagements in Autonomous Vehicles (AVs) being tested on public roads in California.
The dataset you will be using however, while derived from the California Department of Motor Vehicles (DMV) database, has been sufficiently altered to be manageable for this project. As such, the results of the analysis you perform will not directly
represent the California study. The analysis will use statistical and probabilistic approaches to evaluate how well the AI-driven decision and control of AVs works under a variety of conditions and developing insights into why/how they disengage.
Autonomous Vehicles are complex systems that use artificial intelligence (AI) and machine learning (ML) to integrate mechanical, electronic and computing technologies to make real-time driving decisions. Several states in the USA (e.g. California, Texas,
Nevada, Pennsylvania, and Florida) and other parts of the world (e.g. China [1]) have already started field-testing AVs on public roads. As AVs have started interacting more directly with humans on public roads, the safety and resilience of AVs is a significant concern (Uber’s [2] fatal accident, Tesla’s [3] autopilot flaw) and must be thoroughly evaluated through analysis of data obtained during field-testing.
The California DMV mandates that all manufacturers testing AVs on public roads file
annual reports detailing disengagements and accidents. A disengagement occurs when
a failure in the AV system causes control of the vehicle to switch from software to the
human driver.

## Learning Objectives:

In this project, you will study disengagement data from AV manufactures and analyze the
current state of AV safety. The concepts you will learn and apply include the following

1. Handling datasets (Importing, extracting and summarizing features)
2. Basic statistical analysis of the dataset
3. Probabilistic Analysis of the data using concepts from ECE 313 (e.g., Probability,
Conditional Probability, Bayes formula)
4. Create a Naive Bayes Machine Learning model to classify data based on features
(e.g., weather conditions) in the datasetECE/CS 498 DS Spring 2019

## Dataset Description:

In a real-world setting, the data required for analysis might be spread across multiple
sources. That is the case in our analysis too. Below is a description of the raw files in
which the data is available and the data fields in the file. As mentioned previously, the
data has been derived from California DMV, but has been sufficiently modified. Identicality
to a known AV manufacturer is purely coincidental.

**mp1_av_disengagement.csv**: This file lists the details of each disengagement that happened in AV testing.

**mp1_av_totalmiles.csv**: This file contains the total number of miles driven and other summary statistics by month.

## Tasks Description

**Note:** Detailed requirements of following tasks can be found in Project Description document. 

### Task 0 – Getting to know the analysis environment

Before any analysis can be done on a given dataset, you will need to know how to import,
handle and do some basic data manipulation programmatically. This task is designed to
help you get accustomed to the data analysis environment. In doing so, you will also
summarize some of the key performance metrics for evaluating the safety of AVs.

### Task 1 – Basic Analysis of AV Disengagements
Once you are comfortable handling the data, you can start doing some meaningful
analysis. In this task, you will be fitting probability distributions to the data and interpreting
the distributions. You will also understand how interpretation of the distribution provides
us with insights about the data.

### Task 2 – Probabilistic Analysis of AV Disengagement
Humans adapt to the lighting and weather conditions while driving. Given that AV
technology uses sensors like camera and LiDAR whose performance may vary under
different lighting and weather conditions, it becomes paramount to understand if AVs are
able to cope with the change in the environment (sensor performance). The dataset
provided to you has disengagement measurements under different weather conditions
which can help us understand the same.

### Task 3 - Using the Naive Bayes Model
Sometimes, it might be difficult to pinpoint the cause of an AV failure when an accident
or disengagement occurs. This situation might arise when the monitoring system does
not detect the problem, or the logged data gets corrupted. However, with enough correct
data about previous disengagements and their causes, we can predict the cause of theECE/CS 498 DS Spring 2019
latest unknown disengagement. One way to solve this problem is to train a Naive Bayes
classifier based on features in existing data and then feed features of the unknown
disengagement to predict the cause. The usual way of doing that is to split the available
data into a training dataset, which is used to build the Naïve Bayes ML model, and a test
dataset, which is used to evaluate the model. You should be able to interpret the results,
and validity of the assumptions that go into using NB.

