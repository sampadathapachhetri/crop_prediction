# Predictive Modeling for Agriculture

This project predicts crop types based on soil nutrient composition using **Logistic Regression**.  
The goal is to identify which soil feature (Nitrogen, Phosphorus, Potassium, pH) has the strongest predictive performance for classifying crops.  

---

##  Project Workflow
1. **Load and Explore Data**  
   - Checked for missing values  
   - Identified unique crop types  

2. **Preprocessing**  
   - Train-test split  
   
3. **Model Training**  
   - Trained logistic regression models on each soil feature individually  

4. **Evaluation**  
   - Used **weighted F1-score** 
   - Compared performance across features  

5. **Result**  
   - Potassium (K) was found to be the most predictive soil feature.  

---
## Installation

Install all dependencies with:

```bash
pip install -r requirements.txt


