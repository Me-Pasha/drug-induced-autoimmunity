# Drug Induced Autoimmunity Prediction
Dataset used: [Drug Induced Autoimmunity Prediction Dataset (UCI)](https://archive.ics.uci.edu/dataset/1104/drug_induced_autoimmunity_prediction)
## Project Overview
Drug-induced autoimmunity (DIA) refers to the onset of autoimmune responses triggered by certain medications, leading the immune system to mistakenly attack the body’s own tissues. This phenomenon can result in clinical conditions resembling autoimmune diseases such as lupus, hepatitis, or vasculitis. Identifying and predicting drugs with potential to induce autoimmunity is critical for ensuring patient's safety and guiding drug development.

Predictive modeling of DIA involves integrating chemical, biological, and clinical data. Computational approaches typically utilize molecular descriptors derived from chemical structure using RDKit alongside machine learning models trained on known DIA-associated drugs. Using SMILES representation of chemical structure the RDKit can generate molecular discriptors which can be used to train machine learning models. Data consists of known drugs with known possibility of autoimmune risk which are further classified in 'True' of 'False'.

## Project Objective
The main objective of this project is to identify which drug leads to autoimmune risks. Characterstics of drugs are generated through RDKit, an open-source toolkit for cheminformatics, using SMILES (Simplified Molecular Input Line Entry System) representation of chemical structures. This project aims to train and deploy highly accurate machine learning model to predict drug induced autoimmunity with high accuracy.The dataset contains many feature and a classification approach is needed to detect drug leading to autoimmune risks.

In this project we are utilizing the Exploratory Data Analysis (EDA) as a data exploration technique to acquire knowledge, discover new relations, apply new methodologies, and unravel patterns in data. It is important to apply the necessary rationale behind each step to address the main objective of the study.

So, the primary objective of this project is to develop a machine learning model for Drug Induced Autoimmunity Prediction

## Modeling & Evaluation
In this project, several machine learning algorithms were applied to predict drug-induced autoimmunity, and their performance was systematically compared. Among the individual models, K-Nearest Neighbors (KNN) achieved the highest accuracy of 0.85 with an AUC of 0.80, while Support Vector Machine (SVM) also performed competitively with an accuracy of 0.82 and a slightly higher AUC of 0.83. Ensemble methods such as Random Forest (0.81), Gradient Boosting (0.80), and XGBoost (0.79) demonstrated stable but slightly lower accuracies, whereas Naïve Bayes (0.75) and Decision Tree (0.77) showed comparatively weaker predictive capability.

The hybrid ensemble models combining classifiers provided the most promising results. Specifically, the KNN + ANN combination achieved the best performance with an accuracy of 0.88, sensitivity of 0.67, and specificity of 0.94 with AUC of 0.87. The SVM + KNN ensemble also demonstrated strong results with an accuracy of 0.85 and balanced specificity, while the SVM + ANN ensemble maintained a relatively high specificity of 0.96, albeit at the cost of lower sensitivity.

Overall, the findings suggest that while classical models such as KNN and SVM are effective for this dataset, hybrid ensemble approaches, particularly KNN + ANN, offer superior predictive power and robustness. These insights highlight the importance of leveraging ensemble learning strategies in biomedical classification problems, especially when sensitivity and specificity must be balanced for clinical applicability.
