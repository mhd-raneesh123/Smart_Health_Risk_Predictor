# Smart Health Risk Predictor 🩺

This project predicts whether a person is at risk for diabetes using machine learning models like Decision Tree, Random Forest, and XGBoost.

## Dataset
- **Source**: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**: 8 medical features
- **Target**: Diabetes (0 = No, 1 = Yes)

## Steps Followed
1. Loaded and explored the dataset
2. Scaled features using StandardScaler
3. Split data into training and testing sets
4. Trained 3 models:
   - Decision Tree
   - Random Forest
   - XGBoost
5. Evaluated using accuracy, ROC curves, and confusion matrices

##  Results (Example)

| Model           | Accuracy |
|----------------|----------|
| Decision Tree  | 68%      |
| Random Forest  | 75%      |
| XGBoost        | 71%      |

##  Files
- `smart_health_predictor.ipynb` – Main notebook
- `project_report.pdf` – Final report
- ROC and confusion matrix plots

##  How to Use
1. Open the notebook in Google Colab or Jupyter
2. Run all cells
3. View accuracy, classification reports, and visualizations

---

