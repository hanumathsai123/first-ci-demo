# Student Result Prediction ML CI

MLOps Practical-1 and Practical-2 using GitHub Actions.

## Practical-2 ML Pipeline

The CI workflow installs ML libraries, generates a reproducible 300-student dataset, trains a Logistic Regression classifier, evaluates it, saves the model and metrics, and runs automated ML tests.

### Files
- requirements.txt
- train_model.py
- test_ml_pipeline.py
- .github/workflows/ml-ci.yml

### Input Features
- attendance
- internal_marks
- assignment_marks
- previous_score

Target: 1 = PASS, 0 = FAIL.

Generated during CI:
- student_results.csv
- student_result_model.pkl
- metrics.json

### CI Triggers
- push to main
- pull request to main
- manual workflow dispatch
