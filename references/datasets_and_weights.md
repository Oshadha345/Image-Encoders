# Dataset and Weights Guidance

## Recommended dataset strategy
- Primary: ImageNet-100 (class-balanced subset of ImageNet-1K) for iteration speed + strong signal.
- Validation robustness:
  - preferred: full ImageNet-1K validation if available
  - fallback: ImageNet-100 validation + one OOD benchmark
- Optional debugging-only dataset: Tiny-ImageNet (not for final claims)

## Dataset manifest requirements
- Exact class list
- Train/val split definitions
- Checksums for split manifests
- Version/date notes

## Weight requirements
For each model variant used:
- Official supervised pretrained checkpoint at 224 resolution
- 384 resolution checkpoint when available
- Source URL + SHA256 + reference Top-1
- License and usage constraints
- Random-init baseline metadata for from-scratch experiments
