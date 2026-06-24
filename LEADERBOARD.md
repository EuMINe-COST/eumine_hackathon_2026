# Leaderboard — EuMINe DataBridge Hackathon 2026

*Updated: 2026-06-24 10:29 UTC*

Score = `performance_score` (0–40 pts). Baseline score = 20 pts. ✓ = beats baseline.

| Rank | Team | Score /40 | MAE EF (eV/atom) | MAE BG (eV) | Missing |
|------|------|----------:|----------------:|------------:|--------:|
| 1 | CataLIST | **32.76** ✓ | 0.0862 | 0.2561 | 0 |
| 2 | TakeMe2Romania | **29.57** ✓ | 0.1474 | 0.2880 | 0 |
| 3 | ProphX | **23.81** ✓ | 0.2313 | 0.4187 | 0 |

---

Performance score formula (per property): `score_p = 10 + 10 × (baseline_MAE − MAE) / (baseline_MAE − 0.01)` when beating baseline, else `score_p = max(0, 10 × (1 − (MAE − baseline) / baseline))`.

Baseline MAE: formation energy = 0.2378 eV/atom, band gap = 0.6414 eV.
