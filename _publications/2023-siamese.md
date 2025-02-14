---
title: "Predicting dice similarity coefficient of deformably registered contours using Siamese neural network"
collection: publications
category: manuscripts
permalink: 
excerpt: 'Authors: <u>P L Yeap</u>, Y M Wong, A L K Ong, J K L Tuan, E P P Pang, S Y Park, J C L Lee, H Q Tan'
date: 2023-07-28
venue: 'Physics in Medicine & Biology'
slidesurl: 
paperurl: 'https://iopscience.iop.org/article/10.1088/1361-6560/ace6f0/meta'
citation: 
---

Abstract
=====

Objective. Automatic deformable image registration (DIR) is a critical step in adaptive radiotherapy. Manually delineated organs-at-risk (OARs) contours on planning CT (pCT) scans are deformably registered onto daily cone-beam CT (CBCT) scans for delivered dose accumulation. However, evaluation of registered contours requires human assessment, which is time-consuming and subjects to high inter-observer variability. This work proposes a deep learning model that allows accurate prediction of Dice similarity coefficients (DSC) of registered contours in prostate radiotherapy. 

Approach. Our dataset comprises 20 prostate cancer patients with 37–39 daily CBCT scans each. The pCT scans and planning contours were deformably registered to each corresponding CBCT scan to generate virtual CT (vCT) scans and registered contours. The DSC score, which is a common contour-based validation metric for registration quality, between the registered and manual contours were computed. A Siamese neural network was trained on the vCT-CBCT image pairs to predict DSC. To assess the performance of the model, the root mean squared error (RMSE) between the actual and predicted DSC were computed. 

Main results. The model showed promising results for predicting DSC, giving RMSE of 0.070, 0.079 and 0.118 for rectum, prostate, and bladder respectively on the holdout test set. Clinically, a low RMSE implies that the predicted DSC can be reliably used to determine if further DIR assessment from physicians is required. Considering the event where a registered contour is classified as poor if its DSC is below 0.6 and good otherwise, the model achieves an accuracy of 92% for the rectum. A sensitivity of 0.97 suggests that the model can correctly identify 97% of poorly registered contours, allowing manual assessment of DIR to be triggered. 

Significance. We propose a neural network capable of accurately predicting DSC of deformably registered OAR contours, which can be used to evaluate eligibility for plan adaptation.
