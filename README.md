Feature-Driven Analysis of Online Purchase Intent Using SHAP and Predictive Models
📌 Project Overview
This project presents a comprehensive study on predicting and interpreting online purchase intent. By combining high-performance machine learning models with Explainable AI (XAI) techniques, we identify the key drivers of consumer conversion. The study utilizes SHAP (SHapley Additive exPlanations) to provide transparency into model decision-making, offering strategic value for e-commerce optimization.

🔬 Research Highlights:
Core Objective: To identify factors influencing purchase intent and provide interpretable insights for personalized marketing.

Architecture: Evaluated 8 models including XGBoost, SVM, Random Forest, and CatBoost.

Top Performer: CatBoost achieved the highest performance with 89% accuracy.

Interpretability: Used SHAP to quantify the global and local impact of features on purchase probability.

📊 Performance Metrics
Based on our experimental results, the top-performing models achieved the following:

Model	Accuracy	Precision	Recall	F1-Score
CatBoost	89%	0.75	0.60	0.67
XGBoost	88%	0.72	0.59	0.65
Random Forest	88%	0.73	0.54	0.62
SVM	87%	0.73	0.52	0.61
🧠 Explainable AI (XAI) Insights:
Using SHAP summary plots, we identified the most influential features driving "Revenue" outcomes:

PageValues: The strongest predictor; sessions with high page values correlate heavily with completed purchases.

Month: Significant seasonal variations affect intent, with specific months showing higher conversion rates.

ExitRates: A strong negative correlation; high exit rates are a primary indicator of non-conversion.

Administrative Duration: User engagement in administrative areas of the site serves as a key secondary behavioral marker.

🛠️ Repository Structure
Plaintext
├── notebooks/          # Purchase_Intent_Analysis.ipynb
├── reports/            # Full PDF Research Paper
├── requirements.txt    # Environment dependencies
└── README.md           # Project documentation

🚀 Installation & Usage
Clone the repository:
Bash
git clone https://github.com/SHTurja/Online-Purchase-Intent-Analysis.git

Install dependencies:
Bash
pip install -r requirements.txt
Run the analysis:
Execute the Jupyter Notebook located in notebooks/Online_Purchase_Intent_Analysis.ipynb.

👥 Author
Sakibul Hasan Turja - Department of CSE, BRAC University

📄 License
This repository is intended for academic and research purposes. Please cite the included project report when referencing this work.
