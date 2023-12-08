# Binary Classification Model for Network Intrusion Detection



## Project Overview
This project develops a binary classification model focused on network intrusion detection. Utilizing the UNSW_NB15 dataset, the model aims to classify network activities into two classes: attacks (Class 1) and non-attacks (Class 0).

## Model Performance Summary

### Overall Metrics
- **Accuracy**: 91.688% - High rate of correctly classifying both attack and non-attack instances.
- **Precision (Class 1)**: 96.814% - Reliable prediction of network attacks.
- **Recall (Class 1)**: 90.770% - Effective identification of actual attack instances.
- **F1 Score**: 93.695% - Balanced measure of precision and recall.

### Class-wise Performance Analysis

- **Class 0 (Non-Attacks):**
  - **Precision: 83%** - This suggests a moderate rate of false positives, indicating that while the model is fairly accurate in predicting non-attacks, there are instances where it incorrectly labels attacks as non-attacks.
  - **Recall: 94%** - Indicates high sensitivity in detecting true non-attack instances. The model is adept at identifying most of the actual non-attack scenarios.

- **Class 1 (Attacks):**
  - **Precision: 97%** - Denotes a high rate of correctly identified attacks. The model is very effective at pinpointing instances of attacks with minimal false positives.
  - **Recall: 91%** - Confirms the model's effectiveness in capturing attack instances. It successfully identifies a majority of the actual attacks, though there is some room for improvement in recognizing all attack instances.
