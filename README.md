# Experiment No. 1 — Basic Python CI with GitHub Actions

This repository contains **MLOps Experiment No. 1: Basic Python CI with GitHub Actions**.

## Objective

Set up a simple Continuous Integration (CI) pipeline for a Python program using GitHub Actions.

## Project Files

- `result_logic.py` — Python program for the result logic.
- `test_result_logic.py` — Automated unit tests.
- `.github/workflows/ci.yml` — GitHub Actions CI workflow.

## CI Flow

```
Push code to GitHub
        ↓
GitHub Actions starts
        ↓
Set up Python
        ↓
Install dependencies
        ↓
Run automated tests
        ↓
PASS / FAIL
```

## Workflow Triggers

The CI workflow runs when:

- Code is pushed to the `main` branch.
- A pull request is opened against `main`.

## Result

The Python application is automatically tested through GitHub Actions, demonstrating the basic CI process.
