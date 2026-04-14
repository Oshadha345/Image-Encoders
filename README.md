# Image-Encoders

A deep-research workspace for understanding and improving image encoders across CNNs, Transformers, and SSM/VSS models.

## Goal
Build strong observational understanding of encoder internals, identify performance/efficiency gaps, and turn those findings into a novel encoder design with practical edge deployability.

## Research Tracks
- CNNs: ResNet, ConvNeXt
- Transformers: ViT, DeiT, Swin
- SSM/VSS: MambaVision, VMamba, Spatial-Mamba

## Repository Layout
- `docs/` - research templates, protocol, analysis playbooks, and design logs
- `configs/` - YAML templates for data/model/train/eval
- `scripts/` - TODO-only skeleton scripts to implement
- `experiments/` - run manifests and experiment tracking
- `results/` - consolidated tables/plots/metadata
- `weights/` - pretrained weight manifest and checksums
- `references/` - official repos, papers, and file-acquisition guide

## Quickstart (Template Stage)
1. Read `docs/01_scope.md` and finalize questions/hypotheses.
2. Lock training/eval policy in `docs/02_experiment_protocol.md`.
3. Fill `configs/*.yaml` with first milestone settings.
4. Implement `scripts/*.sh` TODOs.
5. Track each run in `experiments/manifests/run_manifest_template.yaml`.
6. Aggregate outputs into `results/tables/` and `results/plots/`.

## First Milestone
- ResNet18 and ResNet50 on ImageNet-100.
- Crop-size sweep: 160, 192, 224, 256, 320.
- Full profile: Top1/Top5, FLOPs, params, latency, memory.
- Deliverables: one comparison table + one analysis report.

## Roadmap
- Phase 1: CNN baselines and crop-size behavior
- Phase 2: ViT/DeiT/Swin under fixed protocol
- Phase 3: MambaVision/VMamba/Spatial-Mamba deep diagnostics
- Phase 4: Gap synthesis and novel architecture proposals
- Phase 5: Ablation and edge deployment validation
