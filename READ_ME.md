# 102217050_Sampling
# Sampling Techniques for Machine Learning Models

This repository contains a Google Colab Notebook demonstrating the application of various sampling techniques to address class imbalance in datasets. The notebook evaluates the performance of these techniques on multiple machine learning models.
---

## 📋 Objective

To explore the impact of sampling techniques on model performance and identify best practices for handling imbalanced data effectively.


---

## 🛠 Techniques Implemented

1. **Oversampling**: Increases the number of minority class samples.
2. **Undersampling**: Reduces the number of majority class samples.
3. **Systematic Sampling**: Selects data at fixed intervals from the dataset.
4. **Stratified Sampling**: Ensures class proportions are maintained in the sampled data.
5. **Cluster Sampling**: Randomly selects clusters and uses them as samples.
6. **Bootstrap Sampling**: Samples data with replacement to create new datasets.

---

## 🤖 Machine Learning Models

The following models were tested with each sampling technique:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**

---

## 📈 Results and Observations

- **Oversampling**: Showed excellent performance on highly imbalanced datasets by improving the representation of minority classes.
- **Stratified Sampling**: Maintained class proportions and was particularly effective for datasets with uneven distributions.
- **Random Forest & Decision Tree**: Consistently achieved high accuracy across most sampling techniques.
- **Cluster Sampling**: Was effective when the clusters were meaningful and representative of the overall dataset.

---

## 📂 Repository Structure

- **Notebook**: Contains all implementations and results for the sampling techniques and model evaluations.
- **Data**: Example datasets for testing the techniques.
- **Results**: Includes performance metrics and visualizations for each technique.

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/dhruvRajoria/SAMPLING/tree/main
   ```
2. Open the Google Colab Notebook and upload the dataset.
3. Follow the steps in the notebook to explore and apply the sampling techniques.

---

## 🙌 Contributions

Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request or open an issue.
---

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.
