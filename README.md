# Euphoria Data Analysis Project Group20-306971
 
## Members
* Angelo Misnik (CAP) - 306971
* Tommaso Di Blasio - 306491
* Margherita Baccheschi - 296621

---

## [Section 1] Introduction
The Euphoria Data project focuses on analyzing and interpreting data from the "Euphoria" dataset. The goal is to uncover insights, trends, and patterns through robust data preprocessing and visualization techniques. This project utilizes Python-based data science libraries to explore the dataset comprehensively.

---

## [Section 2] Methods
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
1. Load Dataset
2. Clean and Preprocess Data
3. Exploratory Data Analysis (EDA)
4. Apply Analytical Methods
5. Generate Visualizations

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
### Main Findings
- Report trends, patterns, or key statistics identified from the analysis.
- Highlight any novel insights extracted from the dataset.

### Placeholder Figures
Include visualizations such as:
1. Bar charts for categorical data distribution.
2. Line plots for trends over time.
3. Heatmaps for correlations between features.

Figures will be generated from the provided code in the notebook.

### Cluster results:
![Cluster_res](https://github.com/user-attachments/assets/7892af53-4cea-40a0-8813-e61422ece22b)

### Boxplot to identify outliers in numerical columns like 'happiness_index'
![happiness_index](https://github.com/user-attachments/assets/cc9aade3-e407-4231-8207-5b010e22caba)

![cluster_1](https://github.com/user-attachments/assets/04b7ce77-4bf2-4408-9bb7-8f0377b32cfc)
![Cluster_2](https://github.com/user-attachments/assets/8f6875e3-df0d-448a-8252-cadde68b050a)

### Random Forest results:
![random_forest](https://github.com/user-attachments/assets/0ba5839e-1191-4f5e-a3e9-fae9842e1bce)

### Gradient boosting regressor
![gradient_b](https://github.com/user-attachments/assets/0eb76a2b-c2f3-4555-97f4-eff22768dca1)

## Train the Best Model
After identifying the best parameters, we can retrain the model using the optimal hyperparameters.+
![training1](https://github.com/user-attachments/assets/3c7d79ea-cf39-47fd-9b71-5e583afe5a7a)
![training2](https://github.com/user-attachments/assets/68d69c2d-87c5-45f9-a51b-33f399522e1a)


---

## [Section 5] Conclusions
### Summary
The Euphoria Data project successfully identifies key patterns and trends, leveraging Python's analytical capabilities to process and visualize the dataset. The findings can provide actionable insights for stakeholders.

### Future Work
Further exploration could involve:
- Implementing advanced machine learning models to predict outcomes based on the dataset.
- Expanding the scope to include additional datasets for comparative analysis.
- Addressing limitations in the dataset, such as missing or incomplete values, to enhance the robustness of results.
