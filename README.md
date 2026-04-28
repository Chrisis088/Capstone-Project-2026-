# Capstone-Project-2026-
Author: Sarah Christie 2306728
This repository contains the implementation of a machine learning pipeline developed to detect indicators of anti-forensic behaviour during digital forensic triage.

## Contents
- capstone_ai_pipeline_v1.ipynb – Main implementation notebook
- Capstone_Final_Dataset.csv – Dataset used for training and evaluation
- Dirty_Files_Pulled - for entropy training 
- Clean_Files_Pulled - for entropy training 

## Description
The pipeline processes forensic artefact metadata and applies feature engineering techniques, including entropy analysis and behavioural indicators, before classifying artefacts using a Random Forest model.

This approach supports early-stage forensic decision-making while maintaining privacy by analysing metadata and statistical features rather than full file contents.

## Note
Due to size and sensitivity considerations, only the final dataset is included. Additional artefacts and intermediate files can be provided upon request.
