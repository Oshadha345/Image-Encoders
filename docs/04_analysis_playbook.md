# 04 Analysis Playbook

## Layer-Level Diagnostics
- Extract stage/block features for all selected checkpoints.
- Run linear probe per stage to assess semantic separability.
- Run similarity analysis (e.g., CKA) for representation evolution.

## Spatial Behavior
- Effective receptive field (ERF) estimation by depth.
- Attention field visualization for Transformer families.
- Scan-path/field analysis for SSM/VSS families.

## Failure and Bias Diagnostics
- Texture vs shape sensitivity probes.
- Frequency bias checks.
- Failure taxonomy by case type:
  - small objects
  - clutter
  - long-tail classes
  - fine-grained confusion

## Output Artifacts
- Standard figure set per model family.
- Comparable plots under shared axis scales.
- Notes linking observations to architectural causes.
