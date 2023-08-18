# Fraud  Detection  With  Graph  Databases  and  Machine  Learning

This project has been implemented as part of the CSE 573 (Semantic Web Mining) course at Arizona State University for the Spring 2023 semester. 
In this project, we aim to identify and classify the fraudulent transactions by employing various machine learning algorithms using graph based features and identify the features that help recognise the fraudulent patterns.
The dataset used for this project is the mix of different dataset, one of them is the BankSim dataset which is a simulated dataset created using a sample of transactional data provided by a bank in Spain (hBankSim, Synthetic data from a financial payment system, Kaggle, 2020 [Online], Available:https://www.kaggle.com/datasets/ealaxi/banksim1).

## Folder Structure 
    .
    ├── data                    # BankSim data files
    ├── code                    # Model and data preprocessing files (Python scripts and notebooks)
    ├── evaluation              # model and eval files
    └── README.md

## Instructions to run the code

All the instructions mentioned below must be run from a terminal session.

- Run the data preprocessing file (SVM_data_load.ipynb).
- Train the data using the respective model files (CODE folder) on the preprocessed data.
- To evaluate, run the respective eval files in the 'Evaluation' folder


## Python libraries used
- NumPy - v1.22.4
- Pandas - v1.5.3
- scikit-learn - v1.2.2
- matplotlib - v3.7.1
- networkx - v3.1
