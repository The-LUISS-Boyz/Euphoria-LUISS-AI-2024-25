# Euphoria Data Analysis Project Group20-306971
 
## Members
* Angelo Misnik (CAP) - 306971
* Tommaso Di Blasio - 306491
* Margherita Baccheschi - 296621

---

## [Section 1] Introduction
The Euphoria Data Analysis Project is an exercise in the exploration, preprocessing, and visualization of data gathered under the "Euphoria" dataset. This project tries to bring out meaningful insights and patterns in the dataset while addressing data quality issues and the implementation of predictive models for actionable outcomes. Using a wide range of Python-based data science libraries and techniques, we will deliver comprehensive insights into the structure and trends within the dataset.
The analysis encompasses:
- **Data Preprocessing**: Cleaning the dataset to handle missing, invalid, or outlier values.
- **Exploratory Data Analysis**: Visualizing relationships, trends, and clusters in the
Dataset.
- **Modeling**: The use of machine learning techniques to predict values and assess the
Performance of Models.
- **Visualization**: Presentation of results with clear and informative plots and charts.

---

## [Section 2] Methods

The project's methodology focuses on clarity, simplicity, and scientific rigor. This includes:

### Proposed Ideas
- **Feature Engineering**: Perform detailed feature extraction to enhance the dataset's utility for analysis.
- **Algorithm Choices**: Utilize visualization techniques and statistical summaries to highlight key trends.
- **Design Decisions**: Focus on simplicity and interpretability while maintaining a robust analytical workflow.

### Environment Setup
This project uses the following libraries and tools:
- Python 3.x
- `pandas` for data manipulation
- `numpy` for numerical computations
- `matplotlib` for data visualization

#### Recreating the Environment
To recreate the environment, install the necessary libraries using:
```bash
pip install pandas numpy matplotlib
```

### Flowchart
Illustrative flowchart describing the analytical pipeline (to be developed further):
1. **Load Dataset**:  Reading the raw dataset for inspection and cleaning.
2. **Clean and Preprocess Data**: Handling missing values, invalid entries, and outliers.
3. **Exploratory Data Analysis (EDA)** Exploring distributions, relationships, and patterns using visualizations.
4. **Training the model**: Training predictive models
5. **Generate Visualizations**: Generating graphs to present key findings.

---

## [Section 3] Experimental Design
### Purpose
To validate the utility of the dataset for generating actionable insights.

### Baselines
- Use summary statistics and standard visualization methods to establish a baseline understanding of the data.

### Evaluation Metrics
- **Data Completeness**: Measure the proportion of missing values.
- **Visualization Effectiveness**: Evaluate the clarity of trends shown in visual outputs.

---

## [Section 4] Results

### Key Observations
The analysis produced several significant findings:
- **Clustering**: Islands were grouped based on geographic, happiness, and other feature values,
revealing unique patterns within the dataset.
- **Predictive Modeling**: Models such as Random Forest and Gradient Boosting were used to
predict the happiness index with notable accuracy.
- **Insights from Boxplots**: Outliers in features like happiness_index and loyalty_score
were identified to refine data quality.

### Main Findings
- Report trends, patterns, or key statistics identified from the analysis.
- Highlight any novel insights extracted from the dataset.

### Placeholder Figures
Include visualizations such as:
1. Bar charts for categorical data distribution.
2. Line plots for trends over time.
3. Heatmaps for correlations between features.

## Figures and explanations 

### Cluster Analysis:
**Island Clusters Based on Happiness and Features**: This scatter plot visualizes the
grouping of islands based on happiness index and feature values. Clusters are color-coded,
with coordinates defining spatial relationships. This visualization highlights the natural
divisions in the dataset.

![Cluster_res](https://github.com/user-attachments/assets/7892af53-4cea-40a0-8813-e61422ece22b)

### Boxplot Analysis:
**Happiness Index Boxplot**: A boxplot summarizing the spread of happiness index values.
The chart identifies the median, interquartile range, and outliers, providing insight into the
distribution and variability of this feature.

![happiness_index](https://github.com/user-attachments/assets/cc9aade3-e407-4231-8207-5b010e22caba)

### Cluster Comparison

**Visualization 1**: A high-resolution scatter plot showing how islands are grouped into
clusters based on happiness and features.

![cluster_1](https://github.com/user-attachments/assets/04b7ce77-4bf2-4408-9bb7-8f0377b32cfc)

**Visualization 2**: Another perspective highlighting slight differences in clustering patterns.

![Cluster_2](https://github.com/user-attachments/assets/8f6875e3-df0d-448a-8252-cadde68b050a)

### Random Forest Regressor
**Predicted vs Actual Plot**: This plot visualizes the predictions of a random forest regressor
against the actual values. Points closer to the red dashed line indicate higher accuracy.

![random_forest](https://github.com/user-attachments/assets/0ba5839e-1191-4f5e-a3e9-fae9842e1bce)

### Gradient boosting regressor
**Gradient Boosting Predictions**: This scatter plot demonstrates the predictions of the
gradient boosting model. The red dashed line indicates perfect predictions, while deviations
reflect model errors.
![gradient_b](https://github.com/user-attachments/assets/0eb76a2b-c2f3-4555-97f4-eff22768dca1)

## Model training
**Visualization of Training Progress**: Plots showing the improvement in training and
validation metrics during model training.
![training1](https://github.com/user-attachments/assets/3c7d79ea-cf39-47fd-9b71-5e583afe5a7a)
![training2](https://github.com/user-attachments/assets/68d69c2d-87c5-45f9-a51b-33f399522e1a)


---

## [Section 5] Conclusions
### Summary
The following project provides some valuable insights into the Euphoria dataset by combining data preprocessing, visualization, and predictive modeling. Important patterns to identify will include island clustering and happiness. Statistical techniques such as boxplots complement the analysis by highlighting data variability and outliers. 

### Future Work
Further exploration could involve:
- Implementing advanced machine learning models to predict outcomes based on the dataset.
- Expanding the scope to include additional datasets for comparative analysis.
- Addressing limitations in the dataset, such as missing or incomplete values, to enhance the robustness of results.
