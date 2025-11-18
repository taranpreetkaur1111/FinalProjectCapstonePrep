# FinalProjectCapstonePrep

# Student Dropout Prediction – Higher Education

This project predicts whether a higher education student will **drop out**, remain **enrolled**, or **graduate**, using demographic, socioeconomic, and academic features available at or shortly after enrollment.

## Dataset

- **Name:** Predict Students' Dropout and Academic Success  
- **Source:** UCI Machine Learning Repository (ID: 697)  
- **Instances:** ~4.4k students  
- **Features:** 36  
- **Task:** Multi-class classification

## Project Structure

- `notebook.ipynb` – main analysis, modeling, and results
- `data/` – dataset (if you store `data.csv` locally)
- `final_report.pdf` – full report (8–10 pages)
- `proposal.pdf` – 1–2 page project proposal
- `README.md` – this file

## How to Run

### **1. Install Dependencies**
#pip install pandas numpy scikit-learn matplotlib


### **2. Load the Notebook**
Open `notebook.ipynb` in Jupyter Notebook, VS Code, or Colab.

### **3. Run All Cells in Order**
The notebook performs:

1. Load & preprocess dataset  
2. Train two models:  
   - Logistic Regression  
   - Random Forest  
3. Generate:  
   - Confusion matrices  
   - Weighted F1-score comparison  
   - Feature importance plot  
   - Correlation heatmap  

All outputs appear inside the notebook.

---

##  Models Used
###  Multinomial Logistic Regression
Baseline linear classifier.

###  Random Forest Classifier
High-performing ensemble classifier.

---

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- Weighted & Macro F1-score  
- Confusion Matrix  

Random Forest consistently performs best in this project.


