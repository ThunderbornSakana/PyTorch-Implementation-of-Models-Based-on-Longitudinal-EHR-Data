# PyTorch Implementation of Models Based on Longitudinal EHR Data
Various deep learning models for learning patient representations from sequential electronic health records (EHR) data have been proposed in recent years. However, some of these works either do not have open source code, or do not have the PyTorch implementation. This repository provides the PyTorch implementation of state-of-the-art deep learning models based on longitudinal EHR data. The standardized code for pre-processing MIMIC-III data is also provided. Two healthcare tasks, diagnosis prediction and mortality prediction, are implemented for all the models included in this repository. Models in this repository are fully supported to run on GPU.

## Requirements
- Python 3.7.13
- PyTorch 1.11.0

## References
[1] Edward Choi, Mohammad Taha Bahadori, Andy Schuetz, Walter F. Stewart, Jimeng Sun. "Doctor AI: Predicting Clinical Events via Recurrent Neural Networks." Machine Learning for Healthcare Conference. 2016.

[3] Edward Choi, Mohammad Taha Bahadori, Le Song, Walter F. Stewart, Jimeng Sun. "GRAM: Graph-based Attention Model for Healthcare Representation Learning." ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. 2017.

[2] Chang Lu, Chandan K. Reddy, Prithwish Chakraborty, Samantha Kleinberg, Yue Ning. "Collaborative Graph Learning with Auxiliary Text for Temporal Event Prediction in Healthcare." International Joint Conferences on Artificial Intelligence. 2021.
