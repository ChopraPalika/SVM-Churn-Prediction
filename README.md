# Customer Churn Prediction using SVM

This project predicts customer churn using the Support Vector Machine (SVM) algorithm.  
Hyperparameter tuning is performed using PyCaret to improve model accuracy.

---

## Files Included
- SVMpred.py  
- customer_churn.csv  
- SVM_Churn_Model.pkl  

---

## Steps in the Project
1. Load and clean dataset  
2. Initialize PyCaret  
3. Train baseline SVM model  
4. Optimize SVM parameters using:
tuned_svm = tune_model(svm_model)


Copy code
5. Finalize and save best model  

---

## Results
- Default SVM accuracy: ~53%  
- Tuned SVM accuracy: ~61% (Linear Kernel)

---

## How to Run
pip install pycaret pandas
python SVMpred.py

## Author
Dr. Palika Chopra
