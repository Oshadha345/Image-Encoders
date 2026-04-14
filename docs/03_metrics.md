# 03 Metrics

## Core Accuracy
- Top-1
- Top-5

## Efficiency
- FLOPs
- Parameter count
- Throughput (images/sec)
- Latency (p50/p90/p99)
- Peak memory usage
- Model artifact size

## Robustness and Calibration
- Crop/resize sensitivity
- Optional OOD benchmark accuracy
- Calibration metrics (e.g., ECE)

## Feature-Quality and Interpretability
- Layer-wise linear probe quality
- CKA/similarity across layers and models
- ERF trend across depth
- Attention/scanning field diagnostics

## Reporting Format
- Per-model summary row
- Per-resolution breakdown
- Per-family aggregated comparison
