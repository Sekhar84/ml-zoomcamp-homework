# ML Zoomcamp 2026 — Homework & Notes

My work for the [Machine Learning Zoomcamp](https://github.com/DataTalksClub/machine-learning-zoomcamp) by [DataTalks.Club](https://datatalks.club/) — a free, 3-month, hands-on ML engineering course running **September–December 2026**.

- Course repo: https://github.com/DataTalksClub/machine-learning-zoomcamp
- Course info / registration: https://datatalks.club/blog/machine-learning-zoomcamp.html
- Curriculum: https://datatalksclub.github.io/docs/courses/ml-zoomcamp/curriculum/
- Cohort start: **September 14, 2026**

## Environment Setup

This repo uses a conda environment named `ml-zoomcamp-2026`.

### Local (Mac/Linux terminal or VS Code)

```bash
conda create -n ml-zoomcamp-2026 python=3.11
conda activate ml-zoomcamp-2026
conda install numpy pandas scikit-learn matplotlib seaborn jupyter
pip install xgboost flask requests gunicorn
```

### Reproducing the environment from a file

Export once (from a machine that already has it set up):

```bash
conda env export -n ml-zoomcamp-2026 --no-builds > environment.yml
```

Recreate anywhere else:

```bash
conda env create -f environment.yml
conda activate ml-zoomcamp-2026
```

### GitHub Codespaces

Codespaces starts a fresh container, so the environment isn't carried over from your local machine automatically.

```bash
conda env create -f environment.yml   # or recreate manually, see above
conda init bash                       # first time only, in a fresh Codespace
# reopen the terminal, then:
conda activate ml-zoomcamp-2026
```

## Course Structure

| # | Module | Topics |
|---|--------|--------|
| 1 | Introduction | Setup, basic Python & pandas, linear algebra refresher |
| 2 | Linear Regression | Predicting car prices — feature engineering, training, evaluation |
| 3 | Binary Classification | Customer churn prediction |
| 4 | Model Evaluation | ROC curves, precision-recall, cross-validation |
| 5 | Model Deployment | FastAPI for serving models, Docker for packaging |
| 6 | Tree-Based Models | Decision trees, random forests, gradient boosting — loan default prediction |
| 7 | **Midterm Project** | Independent 3-week project applying Modules 1–6 |
| 8 | Neural Networks & Deep Learning | PyTorch fundamentals |
| 9 | Serverless Deployment | AWS Lambda with ONNX runtime |
| 10 | Kubernetes | Deploying ML services on Kubernetes |
| 11 | KServe (optional) | Noted as potentially outdated; Kubernetes study recommended instead |
| — | **Capstone Project** | Independent 3-week project following Module 10 |

**Certification** requires completing 2 projects (midterm + capstone, or two capstones) plus peer-reviewing 3 other students' submissions.

## Repo Structure

```
.
├── environment.yml
├── 01-intro/
├── 02-regression/
├── 03-classification/
├── 04-evaluation/
├── 05-deployment/
├── 06-trees/
├── 07-midterm-project/
├── 08-deep-learning/
├── 09-serverless/
├── 10-kubernetes/
├── capstone-project/
└── README.md
```
*(Create module folders as you go — adjust names to match your actual homework layout.)*

## Progress Tracker

| Module | Status | Homework | Notes |
|--------|--------|----------|-------|
| 1. Introduction | ✅ Done | ✅ Done | Q1–Q7 completed, normal equation implemented |
| 2. Linear Regression | 🟡 In progress | | |
| 3. Classification | ⬜ Not started | | |
| 4. Evaluation | ⬜ Not started | | |
| 5. Deployment | ⬜ Not started | | |
| 6. Trees | ⬜ Not started | | |
| 7. Midterm Project | ⬜ Not started | | |
| 8. Neural Networks | ⬜ Not started | | |
| 9. Serverless | ⬜ Not started | | |
| 10. Kubernetes | ⬜ Not started | | |
| Capstone | ⬜ Not started | | |

Update status per module: ⬜ Not started → 🟡 In progress → ✅ Done


## License

Personal coursework — for learning purposes.