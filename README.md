# diabete-prediction-ICT1920066
ICT 4301-Intelligent system project 1

Project Description

This project is a binary classification model built to predict using a custom neural network. It uses structured data and focuses on handling class imbalance, reducing overfitting, and evaluating model performance using appropriate metrics like F1-score and AUC.

**Setup Instructions**

1. Clone the repository

   git clone https://github.com/sithusss/diabete-prediction-ICT1920066
   cd diabete-prediction-ICT1920066
 

2. Create and activate a virtual environment

   python -m venv venv  
   source venv\Scripts\activate  

3. Install dependencies

   pip install -r requirements.txt  
   
**How to Run the Model**

1. Launch the Jupyter Notebook

2. Open the notebook file

   * Navigate to `experiment.ipynb`in the diabete-prediction-ICT1920066 folder


3. Model Workflow Includes

   * Data preprocessing and normalization
   * Handling class imbalance (e.g., using SMOTE)
   * Building a custom Keras model
   * Training with callbacks (EarlyStopping)
   * Evaluation using Accuracy, F1-score, AUC


