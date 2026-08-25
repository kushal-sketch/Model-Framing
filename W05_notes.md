# W05 Deliverable Notes

## Assignment requirements
1. Build the right model/analysis for the lane.
2. Compare it with the W04 baseline on the same data and metric.
3. Use a valid split or validation design.
4. Explain the method choice.
5. Report useful metrics.
6. Interpret features, clusters, or errors.
7. Do not reward complexity alone.
8. Commit `work/notebooks/w05_model.ipynb`.

## Recommended workflow
- Reproduce W04 baseline first.
- Start with Logistic Regression.
- Add Decision Tree for nonlinear structure.
- Add Random Forest for ensemble robustness.
- Use Gradient Boosting only if appropriate.
- Select based on the agreed metric and validation design.

## Validation
Use a stratified split for ordinary binary classification when rows are independent. If rows from the same entity can be dependent, keep the entity/group entirely in either training or evaluation.

## Final table
Include model, primary metric, accuracy, precision, recall, F1, ROC-AUC where appropriate, and delta versus W04 baseline.

## Error analysis
Include a confusion matrix, incorrect-prediction examples, common error patterns, and feature importance or another justified interpretation.

## Final submission
Replace demo data, reproduce W04 baseline, Run All, save the executed notebook, commit it, and submit the GitHub repository URL.
