# Binary Classification Model for Network Intrusion Detection



## Project Overview
This project develops a binary classification model focused on network intrusion detection. Utilizing the UNSW_NB15 dataset, the model aims to classify network activities into two classes: attacks (Class 1) and non-attacks (Class 0).

## Model Performance Summary

### Overall Metrics
- **Accuracy**: 91.688% - High rate of correctly classifying both attack and non-attack instances.
- **Precision (Class 1)**: 96.814% - Reliable prediction of network attacks.
- **Recall (Class 1)**: 90.770% - Effective identification of actual attack instances.
- **F1 Score**: 93.695% - Balanced measure of precision and recall.

### Class-wise Breakdown

    Class 0 (Non-Attacks):
        Precision: 83%, suggesting a moderate rate of false positives.
        Recall: 94%, indicating high sensitivity in detecting true non-attack instances.
    Class 1 (Attacks):
        Precision: 97%, denoting a high rate of correctly identified attacks.
        Recall: 91%, confirming the model's effectiveness in capturing attack instances.
