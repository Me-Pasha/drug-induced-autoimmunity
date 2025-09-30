# Drug Induced Autoimmunity Prediction
## Project Overview
Drug-induced autoimmunity (DIA) refers to the onset of autoimmune responses triggered by certain medications, leading the immune system to mistakenly attack the body’s own tissues. This phenomenon can result in clinical conditions resembling autoimmune diseases such as lupus, hepatitis, or vasculitis. Identifying and predicting drugs with potential to induce autoimmunity is critical for ensuring patient's safety and guiding drug development.

Predictive modeling of DIA involves integrating chemical, biological, and clinical data. Computational approaches typically utilize molecular descriptors derived from chemical structure using RDKit alongside machine learning models trained on known DIA-associated drugs. Using SMILES representation of chemical structure the RDKit can generate molecular discriptors which can be used to train machine learning models. Data consists of known drugs with known possibility of autoimmune risk which are further classified in 'True' of 'False'.

## Project Objective
The main objective of this project is to identify which drug leads to autoimmune risks. Characterstics of drugs are generated through RDKit, an open-source toolkit for cheminformatics, using SMILES (Simplified Molecular Input Line Entry System) representation of chemical structures. This project aims to train and deploy highly accurate machine learning model to predict drug induced autoimmunity with high accuracy.The dataset contains many feature and a classification approach is needed to detect drug leading to autoimmune risks.

In this project we are utilizing the Exploratory Data Analysis (EDA) as a data exploration technique to acquire knowledge, discover new relations, apply new methodologies, and unravel patterns in data. It is important to apply the necessary rationale behind each step to address the main objective of the study.

So, the primary objective of this project is to develop a machine learning model for Drug Induced Autoimmunity Prediction
