# Handling Class Imbalance in Machine Learning

## Overview
This project provides a practical tutorial on handling class imbalance in machine learning. It demonstrates how imbalanced datasets can mislead model performance and explores SMOTE techniqueto improve minority class detection.

---

## Learning Objectives
By working through this tutorial, you will:
- Understand what class imbalance is and why it is a problem
- Learn why accuracy is not a reliable metric for imbalanced data
- Explore techniques such as Oversampling and SMOTE
- Evaluate model performance using Recall and F1-score
- Gain hands-on experience applying SMOTE technique in Python

---

## How to Use This Repository
To get the most out of this tutorial, follow this approach:

1. **Watch the tutorial video**  
   - Follow along with the explanation  
   - Rewind where necessary  
   - Refer to the transcript if any part is unclear  

2. **Run the code yourself**  
   - Download the Jupyter Notebook  
   - Download the dataset and place it in the correct directory (or update the file path)  
   - Execute the notebook step-by-step  

3. **Explore the results**  
   - Observe how class imbalance affects model performance  
   - Compare results before and after applying techniques  

4. **Experiment and modify**   
   - Change parameters (e.g., sampling strategy)  
   - Try different models or features  
   - Observe how results change  

5. **Read further**  
   - Use the references provided in the tutorial for deeper understanding  

---

## Dataset
- Software Defect Prediction Dataset  
- Highly imbalanced binary classification problem  
  - Defect: True
  - Defect: False

---

## Techniques Covered
- Random Oversampling  
- SMOTE (Synthetic Minority Oversampling Technique)  

---

## Experiments
The tutorial includes:
1. Baseline model (no balancing)  
2. Model with SMOTE  

Each experiment compares:
- Confusion Matrix  
- Precision  
- Recall  
- F1-score  
- Visualisations (bar charts)

---

## Key Insight 
Class imbalance techniques such as SMOTE do not directly improve model performance — instead, they provide a **more honest and less biased evaluation** by ensuring the model properly learns from the minority class.

---

## How to Run

1. Install required libraries:
```bash
pip install -r requirements.txt
