# PyTorch Implementation of Models Based on Longitudinal EHR Data
Various deep learning models for learning patient representations from sequential electronic health records (EHR) data have been proposed in recent years. However, some of these works either do not have open source code, or do not have the PyTorch implementation. This repository provides the PyTorch implementation of state-of-the-art deep learning models based on longitudinal EHR data. The standardized code for pre-processing MIMIC-III data is also provided. Two healthcare tasks, diagnosis prediction and mortality prediction, are implemented for all the models included in this repository. Models in this repository are fully supported to run on GPU.

## Requirements
- Python 3.7.13
- PyTorch 1.11.0

## Data Downloading and Preparation
First, please download the following MIMIC-III data files from [PhysioNet](https://physionet.org/content/mimiciii/1.4/) to the directory MIMIC3_data:
- ADMISSIONS.csv
- PATIENTS.csv
- DIAGNOSES_ICD.csv
- D_ICD_DIAGNOSES.csv

Second, please upzip the two zipped files in the directory MIMIC3_data/code_related.

## Implemented Models
Name  | Venue   |  Year
----- | -----   | -----
Doctor AI | Machine Learning for Healthcare | 2016
GRAM  | KDD | 2017
CGL   | IJCAI | 2021

## References
[1] Edward Choi, Mohammad Taha Bahadori, Andy Schuetz, Walter F. Stewart, Jimeng Sun. "Doctor AI: Predicting Clinical Events via Recurrent Neural Networks." Machine Learning for Healthcare Conference. 2016.

[3] Edward Choi, Mohammad Taha Bahadori, Le Song, Walter F. Stewart, Jimeng Sun. "GRAM: Graph-based Attention Model for Healthcare Representation Learning." ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. 2017.

[2] Chang Lu, Chandan K. Reddy, Prithwish Chakraborty, Samantha Kleinberg, Yue Ning. "Collaborative Graph Learning with Auxiliary Text for Temporal Event Prediction in Healthcare." International Joint Conferences on Artificial Intelligence. 2021.
