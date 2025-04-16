
# Predicting High-Traffic Recipes

This project focuses on predicting which recipes will drive high user traffic on a recipe website. Using machine learning and feature analysis, we built a classification model that supports better decision-making for homepage recipe selection—helping increase site engagement and drive subscriptions.

---

##  Project Overview

The product manager currently selects homepage recipes manually, but internal data shows that featuring a **popular recipe can boost site traffic by up to 40%**. The business goal was to:

- **Predict which recipes will lead to high traffic**
- **Correctly identify at least 80% of high-traffic recipes (recall)**

We developed and deployed a **Random Forest model** that achieved **76% recall**, making it a reliable decision support tool for homepage content strategy.

---

##  Key Deliverables

- ✅ Data cleaning & validation  
- ✅ Exploratory data analysis (EDA)  
- ✅ Category and nutrition-based feature engineering  
- ✅ Binary classification using Logistic Regression and Random Forest  
- ✅ Hyperparameter tuning and model evaluation  
- ✅ Business-oriented slide presentation

---

##  Performance Highlights

| Model                 | Precision (High) | Recall (High) |
|-----------------------|------------------|---------------|
| Logistic Regression   | 83%              | 75%           |
| Random Forest (Final) | 78%              | 76%           |

 **Primary KPI:** Recall (High-Traffic) – 76%  
This means the model successfully captures the majority of popular recipes, helping guide homepage selections with confidence.

---

##  Feature Importance (Top Drivers)

- **Protein**
- **Calories**
- **Carbohydrates**
- **Vegetable, Potato, and Pork categories**

These features showed the strongest influence on recipe popularity.

---

##  Project Structure

```
high-traffic-recipes/
├── data/               # Dataset
├── notebook/           # Jupyter notebook with full workflow
├── presentation/       # project presentation slides
├── images/             # Visualizations and plots
├── README.md           # Project summary (this file)
└── requirements.txt    # Dependencies
```

---

##  Business Recommendations

1. **Deploy the Random Forest model** to assist in daily homepage recipe decisions  
2. **Feature top-performing categories** (Vegetable, Potato, Pork) to drive traffic  
3. **Use nutrition features** to tailor high-engagement recipe recommendations  
4. **Monitor and retrain the model** regularly to stay current with evolving trends  
5. **Improve model recall via A/B testing** and threshold tuning to meet the 80% target  

---

##  Target Audience

- **Product Manager** responsible for homepage content  
- **Stakeholders** interested in data-driven engagement strategies  
- **Data Science Teams** building scalable, interpretable models

---

##  Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

##  Author

**Victor Kioko Mutua**  
*Aspiring Data Scientist | ALX & DataCamp Certified*  
🔗 [LinkedIn](https://www.linkedin.com/in/mutuavictor)

