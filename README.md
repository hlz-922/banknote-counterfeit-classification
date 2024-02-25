# banknote-counterfeit-classification

### **Project Description**

- The main objective is to create a classifier capable of accurately identifying counterfeit banknotes based on a dataset derived from images taken from both genuine and counterfeit banknotes using an industrial camera.
- The dataset utilizes Wavelet Transformation (WT) to extract features from these images, including variance, skewness, kurtosis, and entropy, which serve as the basis for classification.
- The assignment covers essential steps like data splitting into training and testing sets, k-fold cross-validation for parameter tuning, and performance evaluation using accuracy, ROC curve, and AUC metrics.

### **Key Steps**

1. **Setup:** Import the necessary libraries for the project, focusing on **`sklearn`** for its comprehensive tools in model training, validation, and metrics evaluation.
2. **Data Loading:** Two datasets are loaded - one for training the model (**`df`**) and another as a held-out test set (**`df_eval`**) for final model evaluation.
3. **Preprocessing:** The provided instructions likely include preprocessing steps to clean and prepare the data for modeling, aligning the treatment of both training and evaluation datasets.
4. **Model Training:** Utilize the Decision Tree classifier for the task, with a focus on understanding and applying the right preprocessing and feature extraction techniques.
5. **Model Validation and Tuning:** Apply k-fold cross-validation to tune the classifier's parameters, ensuring the model's generalizability and robustness.
6. **Performance Evaluation:** After training, evaluate the model's accuracy on the test set and use ROC and AUC metrics for a comprehensive assessment of its classification capability.
