# 📘 SVM Optimization 

This project focuses on optimizing Support Vector Machine (SVM) classification for a multi-class dataset selected from the UCI Machine Learning Repository. The SVM model is tuned across 10 different random train-test samples using 100 iterations each. The performance and convergence of each sample are evaluated to find the best configuration.

---

## 🎯 Objective

- Use a multi-class dataset with 5k–30k rows from UCI.
- Divide the dataset into 70% training and 30% testing.
- Generate 10 different samples using different random seeds.
- Optimize SVM parameters (`kernel`, `nu`, `epsilon`) for each sample.
- Perform 100 optimization iterations for each sample.
- Track and report the best accuracy and parameters.
- Plot a convergence graph of the best-performing sample.
- Include basic data analytics of the dataset.
- Share the full code and results via this GitHub repository.

---

## ⚙️ Methodology

1. **Data Preprocessing:**
   - Load dataset, handle missing values, encode categorical features.
   - Standardize feature values.

2. **Train-Test Splitting:**
   - Create 10 random samples using different seeds.
   - Apply 70-30 train-test split on each.

3. **SVM Optimization:**
   - Perform parameter tuning for `kernel`, `nu`, and `epsilon`.
   - Use 100 iterations per sample (e.g., using Grid Search, Genetic Algorithm, or PSO).
   - Store best parameters and accuracy for each sample.

4. **Evaluation:**
   - Record accuracy and optimal parameters in a results table.
   - Plot convergence graph (accuracy vs iteration) for the best sample.

5. **Data Analytics:**
   - Plot class distribution, correlations, PCA/t-SNE visualization, etc.

---

## 🧪 Basic Data Analytics

- Class distribution bar chart  
- Feature correlation heatmap  
- PCA / t-SNE visualization of feature space  
- Box plots and histograms of selected features  

---

## 🧰 Tools & Libraries

- **Language:** Python 3.x  
- **Libraries:**  
  - `pandas`, `numpy` for data handling  
  - `scikit-learn` for SVM, preprocessing, train-test split  
  - `matplotlib`, `seaborn` for plotting  
  - `deap`, `optuna` or custom code for optimization (optional)
