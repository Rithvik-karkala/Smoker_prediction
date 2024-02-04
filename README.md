# Predicting Smoking Status using Machine Learning

## Overview

This repository contains a machine learning model designed to predict whether an individual is a smoker or not based on various health-related features. The dataset includes columns such as age, height, weight, waist circumference, eyesight, hearing ability, blood pressure, cholesterol levels, and several other health indicators.

## Dataset Description

- **Age:** The age of the individual.
- **Height (cm):** The height of the individual in centimeters.
- **Weight (kg):** The weight of the individual in kilograms.
- **Waist (cm):** Waist circumference measurement.
- **Eyesight (left and right):** The eyesight measurement for the left and right eyes.
- **Hearing (left and right):** The hearing ability for the left and right ears.
- **Systolic and Diastolic Blood Pressure:** Blood pressure measurements.
- **Cholesterol Levels (HDL, LDL):** High-density lipoprotein (HDL) and low-density lipoprotein (LDL) cholesterol levels.
- **Hemoglobin:** Blood hemoglobin levels.
- **Urine Protein:** Presence of protein in urine.
- **Serum Creatinine:** Serum creatinine levels.
- **AST, ALT, Gtp:** Liver function test parameters.
- **Dental Caries:** Presence of dental caries.

## Problem Statement

The primary objective is to develop a machine learning model that accurately predicts whether an individual is a smoker based on the provided health indicators. Smoking status prediction can have important implications for public health research and personalized healthcare interventions.

## Model Building

Two classification models were evaluated: Linear Regression and XGBoost Classifier. The models were trained on a labeled dataset with features as input and smoking status as the target variable.

- **Linear Regression:** This model assumes a linear relationship between the features and the target variable. However, it may not capture complex, non-linear patterns present in the data.

- **XGBoost Classifier:** XGBoost is an ensemble learning algorithm that combines the predictions of multiple decision trees. It is well-suited for classification tasks and can handle non-linear relationships effectively.

The XGBoost Classifier outperformed Linear Regression in terms of accuracy, making it a more suitable choice for this prediction task.

Thanks,
Rithvik
****************************************************************************************
