# Heart Disease Prediction (UCI Cleveland)

**Course:** SE309 – AI and Data Science for Innovation in Health Science  
**Topic code:** SE309-02  
**Working as:** Individual

## Project member

| Full name | Student number | GitHub username |
|---|---|---|
| LEONCIO NSUE NKILI ASANGONO | 220201902 | leoncionsuen12-arch |

## What the project does

This project uses the UCI Cleveland dataset to compare logistic regression and a decision tree with a majority-class baseline. The notebook explores the data, trains the models, and evaluates them on the same test set using accuracy, sensitivity, specificity, and confusion matrices. It also uses permutation importance to examine which variables contributed most to logistic regression predictions. The project is intended for academic analysis.

## How to run the notebook

1. Open [notebooks/project.ipynb](notebooks/project.ipynb) in this repository.
2. Click **Open in Colab**. If the button is missing, open Google Colab, choose **File → Open notebook → GitHub**, and paste this repository's URL.
3. In Colab, select **Runtime → Run all**. The notebook loads the dataset directly from UCI.

## Data source

| Dataset | Source | Size | License |
|---|---|---|---|
| UCI Heart Disease, processed Cleveland file | [UCI Machine Learning Repository](https://doi.org/10.24432/C52P4X) | 303 records, 13 input variables, and one target | CC BY 4.0 |

## Results

| Model | Accuracy | Sensitivity | Specificity |
|---|---:|---:|---:|
| Majority baseline | 53.9% | 0.0% | 100.0% |
| Logistic regression | 88.2% | 88.6% | 87.8% |
| Decision tree | 78.9% | 80.0% | 78.0% |

Logistic regression correctly identified 31 of the 35 records with heart disease in the test set. These results come from one test split of 76 records.

## Repository structure

- `README.md` — Project overview and instructions.
- `notebooks/project.ipynb` — Data exploration, model training, results, and limitations.

## Contributions

I assembled the notebook in Google Colab, ran the code cells, and verified the dataset size, class counts, and model results against the Colab outputs.

## Libraries and AI tools

- **pandas** — Data loading, exploration, and result tables.
- **Matplotlib** — Distribution plots and confusion matrix displays.
- **scikit-learn** — Data preparation, model training, evaluation, and permutation importance.
- **ChatGPT** — Helped develop and refine the Python code, and interpret the Colab results.
