# Official Sources and Required Files Guide

## Required from each external repository (minimum)
- Model definitions (backbone, block modules, stage composition)
- Training engine/loop
- Data pipeline and augmentations/transforms
- Optimizer/scheduler/loss setup
- Canonical ImageNet config files
- Checkpoint loading/conversion utilities
- Evaluation/inference scripts
- LICENSE file and exact commit hash

## Suggested official repositories
- ResNet: https://github.com/pytorch/vision (or timm implementation references)
- ConvNeXt: https://github.com/facebookresearch/ConvNeXt
- ViT: https://github.com/google-research/vision_transformer
- DeiT: https://github.com/facebookresearch/deit
- Swin: https://github.com/microsoft/Swin-Transformer
- MambaVision / VMamba / Spatial-Mamba: official repos linked by papers

## Reproducibility policy for external code
- Record exact repo URL and commit hash used.
- Record local file paths imported/adapted.
- Preserve license attribution notes.
- Track any local modifications separately.
