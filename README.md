# W05 Model Build — GitHub Ready

## Main deliverable
`work/notebooks/w05_model.ipynb`

## What it covers
- Method choice and rationale
- Valid split design
- Baseline comparison
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Accuracy, precision, recall, F1 and ROC-AUC
- Confusion matrix and error inspection
- Permutation importance
- Final self-check

## Important
`data/w04_data.csv` is demo data so the notebook executes immediately. Replace it with the exact Week-4 dataset and reproduce the exact Week-4 baseline/split/primary metric before submitting.

## VS Code
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

Open the notebook in VS Code and **Run All**.

## GitHub
```bash
git add work/notebooks/w05_model.ipynb data/w04_data.csv requirements.txt README.md docs/W05_notes.md
git commit -m "Add W05 model build and baseline comparison"
git push
```
