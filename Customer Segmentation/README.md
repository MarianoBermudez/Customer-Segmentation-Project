# Mall Customer Segmentation

## Introduction
This project uses the [Mall Customer Segmentation dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) to group customers using K-means clustering. The goal is to identify customer types for better marketing strategies.

---

## About the Dataset
The dataset includes:
- **Age**
- **Gender**
- **Annual Income (k$)**
- **Spending Score (1-100)**

The Spending Score represents customer behavior and purchase habits. The project helps identify target customers for focused marketing.

---

## Steps
1. **Load and Clean Data**:
   - Dropped unnecessary columns.
   - Renamed and encoded features for analysis.

2. **Visualize Data**:
   - Explored relationships using pair plots, scatter plots, and heatmaps.

3. **K-means Clustering**:
   - Used the Elbow Method to find the best number of clusters.
   - Grouped customers into 5 types based on income, spending score, and age.
   - Visualized clusters in 2D and 3D.

4. **Logistic Regression**:
   - Built a model to predict customer types.
   - Achieved 90% accuracy.

5. **Save Results**:
   - Exported processed data and saved models for reuse.

---

## Customer Types
1. **Type 0**: Young, low income, high spending score.
2. **Type 1**: Middle-aged, high income, medium spending score.
3. **Type 2**: Middle-aged, high income, high spending score.
4. **Type 3**: Older, high income, low spending score.
5. **Type 4**: Older, low income, low spending score.

---

## Results
- **Insights**: Understand customer behavior for targeted marketing.
- **Models**: Predict customer types using clustering and logistic regression.
- **Files**: Processed data (`processed_data.csv`) and saved models (`km_model.pkl`, `lr_model.pkl`).
