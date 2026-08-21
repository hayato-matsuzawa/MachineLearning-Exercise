# Kaggriculture V9 selector training

No newest-holdout row was loaded. Hyperparameters selected by bidirectional era transfer, grouped episode CV, and temporal block CV.

- Winner: `d1:constant(candidate=1)`
- Decision step: 1
- Training samples: 94
- Training episodes: 47

## Cross-validation folds

| Fold | Wins | N | Win rate | Mean margin | Min margin |
|---|---:|---:|---:|---:|---:|
| public_to_mid | 35 | 40 | 87.50% | 12524.4 | -26840.0 |
| mid_to_public | 48 | 54 | 88.89% | 28032.4 | -8255.0 |
| episode_cv_0 | 20 | 20 | 100.00% | 33738.8 | 4915.0 |
| episode_cv_1 | 10 | 20 | 50.00% | 12402.2 | -26840.0 |
| episode_cv_2 | 17 | 18 | 94.44% | 14139.3 | -2612.0 |
| episode_cv_3 | 18 | 18 | 100.00% | 26829.7 | 1154.0 |
| episode_cv_4 | 18 | 18 | 100.00% | 19692.3 | 4038.0 |
| public_v18_live_early_to_late | 14 | 16 | 87.50% | 13024.8 | -6705.0 |
| public_v18_live_late_to_early | 34 | 38 | 89.47% | 34351.4 | -8255.0 |
| mid_teacher_holdout_early_to_late | 10 | 12 | 83.33% | 11442.9 | -26840.0 |
| mid_teacher_holdout_late_to_early | 25 | 28 | 89.29% | 12987.9 | -5271.0 |
