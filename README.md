# Preterm Birth Detection using Electrohysteography (EHG)

This project aims to predict preterm births using Electrohysteography (EHG) signals collected from mothers before week 26 of pregnancy. The analysis is done in Python, utilizing machine learning techniques.

## Background

Preterm birth is a significant global health issue, with potential complications leading to neonatal deaths and various medical conditions. This project explores the use of EHG signals, collected from the surface of the uterus, to differentiate between mothers with preterm births and those with normal pregnancies.

## Objective

The objective of this project is to develop a machine learning model that can classify EHG signals into two classes: 1 for preterm births and 0 for normal pregnancies. The analysis includes preprocessing, feature extraction, and training classifiers to predict preterm births using leave-one-out cross-validation.

## Dataset

The dataset used in this project is sourced from the Physionet Term-Preterm EHG Database. It includes EHG recordings from mothers with normal pregnancies (20 records) and those who gave preterm birth (19 records). Each record contains 30-minute EHG signals captured from four electrodes.

## Instructions

1. Preprocessing: Apply filtering techniques as necessary to enhance the quality of EHG signals.
2. Feature Extraction: Extract relevant time-domain and frequency-domain features from the EHG signals using packages such as scipy, tsfresh, and tsfel.
3. Machine Learning: Train two classifiers using scikit-learn to predict preterm or normal pregnancies based on the extracted features.
4. Evaluation: Utilize leave-one-out cross-validation to evaluate the performance of the classifiers, considering accuracy, precision, recall, and f1-score.

## Getting Started

To get started with the project, follow these steps:
1. Clone the repository.
2. Set up the Python environment and install the required packages.
3. Convert .html file to .py/.ipynb and run the script to filter the EHG signals and extract features from the preprocessed signals.
4. Train and evaluate the classifiers using the script.
5. Explore the results, including accuracy and other evaluation metrics.

## Project Structure

- `data/`: Contains the dataset files, including records from normal and preterm pregnancies.
- `EHG project (1).py`: Script for preprocessing EHG signals, extracting features, and training ML Classifiers.
- `README.md`: Project documentation and instructions.

## Contributions and Acknowledgements

- Contributors: [Sohaib Zafar], [Sanna Herrala]
- Special thanks to [Iman Azimi] for guidance and support during the project.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
