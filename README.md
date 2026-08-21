# Data Science and Machine Learning Notes

This repository contains short Jupyter notebook lessons and practice work in Python.

## Notebook Notes

- **ML foundations (`vid-4` to `vid-7`):** batch vs. online learning, instance-based vs. model-based learning, and common machine-learning challenges such as poor data, bias, overfitting, and underfitting.
- **Data understanding (`vid-19`):** load a CSV with pandas and inspect its shape, samples, data types, missing values, summary statistics, duplicates, and correlations.
- **EDA (`vid-20`, `Practice/vid-20`):** use Seaborn and Matplotlib for count plots, pie charts, histograms, KDE distributions, box plots, scatter plots, and skewness checks on placement and cricket data.
- **Bivariate and multivariate analysis (`vid-21`):** compare numerical and categorical variables with scatter plots, bar plots, box plots, heatmaps, clustermaps, pair plots, and line plots.
- **Automated profiling (`vid-22`):** create an HTML Titanic data-quality and statistics report with `ydata-profiling`; the generated report is `titanic_profile_report.html`.
- **Feature preparation (`vid-23` to `vid-25`):** learn feature transformation, construction, selection, standardization, and min-max normalization. Scaling is especially important for distance- or gradient-based algorithms such as KNN, K-Means, PCA, neural networks, and gradient descent.
- **Classification example (`vid-13`):** prepare the placement dataset, remove the index column, split and standardize features, train logistic regression, measure accuracy, visualize decision regions, and save the model with `pickle`.

### Typical Workflow

1. Load and inspect the data.
2. Clean and validate types, missing values, duplicates, and outliers.
3. Explore distributions and relationships visually.
4. Engineer and scale features when the algorithm requires it.
5. Split the data, train the model, evaluate it, visualize results, and save reusable artifacts.

The notebooks use Python 3.12+, pandas, Seaborn, Matplotlib, scikit-learn, and ydata-profiling. Run notebooks from the repository root so relative CSV paths resolve correctly.
