## Project 1: Mini-AutoML

A simplified AutoML system for **binary classification**, designed to automatically select the best model and configuration for a given dataset.

### Key Contributions
- Designed and evaluated a diverse portfolio of ML models, including Logistic Regression, SVM, Random Forest, XGBoost, kNN, and boosting methods.
- Performed hyperparameter analysis and selected representative configurations for each model family.
- Conducted experiments on OpenML datasets to identify the most effective model setups.
- Implemented a model selection strategy based on performance, stability, and diversity across algorithm families.
- Built a complete ML pipeline with preprocessing, validation, model ranking, and automatic decision-threshold tuning.
- Developed an automatic selection mechanism for choosing either the best single model or a soft-voting ensemble.
- Optimized the solution for efficiency and scalability.

### Outcome
The system automatically evaluates multiple models, selects the best-performing one, tunes the classification threshold, and optionally builds an ensemble. The strongest results were achieved by kNN and tree-based ensemble methods.

---

## Project 2: Hyperparameter Tuning Analysis

A comparative study of **hyperparameter tunability and optimization methods** across different machine learning models and datasets.

### Key Contributions
- Compared three ML models: Logistic Regression, Random Forest, and XGBoost.
- Evaluated two hyperparameter optimization approaches: Randomized Search and Bayesian Optimization.
- Ran experiments on four datasets from different domains, including medical, financial, and weather data. 
- Analyzed model performance using ROC-AUC and stability metrics.
- Developed a methodology for measuring tunability based on performance differences between tuned and default hyperparameters.
- Created visual analyses such as heatmaps and boxplots to study sensitivity to hyperparameters and performance variability.
- Investigated convergence speed, the impact of iteration count, and robustness across different train/test splits.

### Key Findings
- XGBoost showed the highest tunability and gained the most from hyperparameter optimization.
- Random Forest had moderate, dataset-dependent sensitivity to tuning.
- Logistic Regression was the most stable and the least sensitive to hyperparameter changes.
- Random Search and Bayesian Search produced similar overall results.
- All models achieved strong ROC-AUC scores, with XGBoost exceeding **0.97** on selected datasets.
