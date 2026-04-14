# 02 Experiment Protocol

## Fixed Cross-Family Settings
- Input resolutions to compare: `{160, 192, 224, 256, 320}`
- Keep augmentation policy constant across model families.
- Keep optimizer family, weight decay policy, EMA policy, and LR schedule family constant.
- Keep train-budget policy constant (epochs or compute-normalized budget).
- Keep evaluation protocol constant (single-crop and optional multi-crop, fixed seeds).

## Reproducibility Rules
- Log: config hash, git hash, seed, hardware, framework versions.
- Use deterministic seed policy and document unavoidable nondeterminism.
- Record exact dataset manifest/checksums for each run.

## Fairness Rules
- Avoid hidden family-specific tuning unless documented as separate ablation.
- Compare models at matched protocol first; only then run family-optimized settings.
