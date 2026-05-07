# Baseline Model

This folder contains the baseline script used in Stage 1.

Run from project root:

```bash
python baseline/baseline_model.py
```

Expected outputs (generated locally, not tracked):

- `baseline_results.csv`
- `baseline_model_ef.joblib`
- `baseline_model_bg.joblib`
- `baseline_constants.py`

Copy `BASELINE_MAE_EF` and `BASELINE_MAE_BG` from `baseline_constants.py`
into `evaluation_bundle/scoring_program/evaluate.py` before building the Codabench bundle.
