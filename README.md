


# CORe Model - Clinical Diagnosis Prediction

## Model description

The CORe (_Clinical Outcome Representations_) model is introduced in the paper [Clinical Outcome Predictions from Admission Notes using Self-Supervised Knowledge Integration](https://www.aclweb.org/anthology/2021.eacl-main.75.pdf).
It is based on BioBERT and further pre-trained on clinical notes, disease descriptions and medical articles with a specialised _Clinical Outcome Pre-Training_ objective.

This model checkpoint is **fine-tuned on the task of diagnosis prediction**.
The model expects patient admission notes as input and outputs multi-label ICD9-code predictions.

#### Model Predictions
The model makes predictions on a total of 9237 labels. These contain 3- and 4-digit ICD9 codes and textual descriptions of these codes. The 4-digit codes and textual descriptions help to incorporate further topical and hierarchical information into the model during training.



