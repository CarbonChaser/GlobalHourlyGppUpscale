# Upscale Global Hourly GPP with Temporal Fusion Transformer

Authors: Rumi Nakagawa[^*], Mary Chau[^*], John Calzaretta[^*], 

UC Berkeley iSchool MIDS program: Capstone Spring 2023

Website: [http://carbonchaser.wixsite.com/globalupscale](http://carbonchaser.wixsite.com/globalupscale)

Research Paper: [http://arxiv.org/abs/2306.13815](http://arxiv.org/abs/2306.13815)

## Abstract
Reliable estimates of Gross Primary Productivity (GPP), crucial for evaluating climate change initiatives, are currently only available from sparsely distributed eddy covariance tower sites. This limitation hampers access to reliable GPP quantification at regional to global scales. Prior machine learning studies on upscaling in situ GPP to global wall-to-wall maps at sub-daily time steps faced limitations such as lack of input features at higher temporal resolutions and significant missing values. This research explored a novel upscaling solution using Temporal Fusion Transformer (TFT) without relying on past GPP time series. Model development was supplemented by Random Forest Regressor (RFR) and XGBoost, followed by the hybrid model of TFT and tree algorithms. The best preforming model yielded to model performance of 0.704 NSE and 3.54 RMSE. Another contribution of the study was the breakdown analysis of encoder feature importance based on time and flux tower sites. Such analysis enhanced the interpretability of the multi-head attention layer as well as the visual understanding of temporal dynamics of influential features.

[^*]: All three authors contributed equally to this research.
