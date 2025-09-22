# 🚢 Titanic Survival Prediction

Titanic Survival Analysis & Modeling
 

---
## The Lowdown
We’re diving into Titanic’s passenger data to see who made it out alive.  
Simple goal: feed some ML models, get those survival predictions.

---
## Dataset
- **Source:** [Kaggle – Titanic](https://www.kaggle.com/c/titanic)  
- **Train:** 891 rows × 12 cols  
- **Test:** 418 rows × 11 cols  
- **Key Features:** Age, Sex, Pclass, Fare, FamilySize, Embarked, Title

---
## What We Did
1. **Explored the data** – missing values, distributions, outliers  
2. **Cleaned it up** – filled Age & Embarked, simplified Cabin, dropped irrelevant stuff  
3. **Feature Engineering:**  
   - FamilySize & FamilyType 
   - Titles from Name (`Mr`, `Mrs`, `Miss`, `Master`, Rare)  
   - Binned Age & Fare (young, adult, senior / low → high)  
4. **Encoded categorical features**  
5. **Model Time:** Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, SVM  
6. **Checked performance:** Accuracy, Precision, Recall, F1

---
## Quick Results

| Model | Accuracy | Precision | Recall | F1 |
|-------|----------|-----------|--------|----|
| Logistic Regression | 0.804 | 0.783 | 0.681 | 0.729 |
| Decision Tree       | 0.782 | 0.742 | 0.667 | 0.702 |
| Random Forest       | 0.816 | 0.765 | 0.754 | 0.759 |
| Gradient Boosting   | 0.816 | 0.833 | 0.652 | 0.732 |
| SVM                 | 0.816 | 0.781 | 0.725 | 0.752 |

---
## Tech Stack
Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn

---

## Next Moves
- Hyperparameter tuning  
- Feature importance vibes  
- Maybe deploy it in a web app 🚀
