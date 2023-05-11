# Upscale Global Hourly GPP through Temporal Fusion Transformer

Authors: John Calzaretta[^*], Mary Chau[^*], Rumi Nakagawa[^*]

UC Berkeley iSchool MIDS program: Capstone Spring 2023

Website: [http://carbonchaser.wixsite.com/globalupscale](http://carbonchaser.wixsite.com/globalupscale)

Research Paper:  <Under Review>

## Abstract
With increasing attention and investments in carbon reduction initiatives from both public and private sectors, reliable estimates of carbon flux, including Gross Primary Productivity (GPP), are crucial for assessing the accountability and effectiveness of climate change initiatives. FLUXNET provides empirical estimates of GPP based on the measured Net Ecosystem Exchange (NEE) in flux towers. However, global estimates of GPP continue to have high uncertainty, due to the limited number of flux sites that provide CO\textsubscript{2} fluxes.  Some machine learning models applied to GPP upscaling had limited performance due to lack to predictor features at higher temporal resolutions and irregularity in the number and distributions of missing values. With the focus on developing a global upscaling model for hourly GPP, this research explored a novel application of Temporal Fusion Transformer (TFT) on time-series problem without the availability of past target values. Model development was supplemented by Random Forest Regressor (RFR) and XGBoost (XGB), followed by the hybrid model of TFT and tree algorithms. As a result, one of the developed models outperformed the latest study by 2.9\% improvement in NSE (70.4\%) and 10.2\% of improvement in RMSE (3.54). Additionally, this study utilize interpretable outputs of TFT to analyze model results and the temporal dynamics of feature importance per prediction. The study lays the foundation for future utilization of TFT in addressing generic upscaling problems across various fields.

[^*]: All three authors contributed equally to this research
