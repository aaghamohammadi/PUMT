# Introduction

This repository includes the experimental implementation of a paper entitled
*The Threat to the Validity of Predictive Mutation Testing: The Impact of Uncovered Mutants* ([link](https://arxiv.org/abs/2005.11532)).

In this paper, we show that the uncovered mutants could reduce the results of predictive mutation testing considerablly. To investigate 
our hypothesis we perform the following three steps:

### Step 1: Replication
We replicate the study of previous predictive mutation testing ([link](https://github.com/SElab2019/ExtPMT)). However, we take uncovered mutants
into account when we evaluate the model. The results show that the AUC drops from 0.83 to 0.51.

### Step 2: Proposed approach

We proposed an approach heavily based on ensemble techniques. The proposed approach used Random Forest and Gradient Boosting to predict
the results of mutant execution.


# Structure

In order to use this repository, you need to first download the dataset provided by Mao ([link](https://github.com/SElab2019/ExtPMT)). We would
like to thank Mao for making the data publicly available. Our research is impossible without that data. 

Afer downloading the data, you should put the unzip thereof on the folder ```docs/Data``` . Now, you are able to run the experiments
written in the Python programming language. We use jupyter notebooks for running the code.
