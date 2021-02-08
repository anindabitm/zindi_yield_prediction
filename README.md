# zindi_yield_prediction
A CNN LSTM based solution for yield prediction

About challenge: https://zindi.africa/competitions/cgiar-crop-yield-prediction-challenge

Crop yield data is arguably the most important measure of agricultural productivity and production, and is used to monitor global and national food security, and to help determine effective agricultural policy.

Due to the physical challenges and high costs associated with the collection of crop-cut yield estimates, few datasets exist and even fewer are regularly sampled every season. For this reason, developing new methods to estimate crop yields at scale using the limited data available has been a prominent research priority.

One of the most promising yield estimation methods has been to use available crop-cut datasets to calibrate mathematical models to estimate crop yields from satellite imagery.

The aim of this challenge is to create a model capable of estimating the crop-cut maize yield for fields in East Africa. Given a time-series of Sentinel 2 imagery and climate variables, your model must output a predicted yield in tons per acre.

These models often need to be applied at scale, so large ensembles are discouraged. To incentivise more lightweight solutions, we are adding an additional submission criteria: your submission should take a reasonable time to train and run inference. Specifically, we should be able to re-create your submission on a single-GPU machine (eg Nvidia P100) with less than 8 hours training and two hours inference.
