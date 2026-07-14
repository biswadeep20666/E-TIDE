<div align="center">

# 🌊 E-TIDE ⚡

## Fast, Structure-Preserving Motion Forecasting from Event Sequences

### Official implementation of our IROS 2026 paper

</div>

---

## At a Glance

### Single pass. No diffusion.

E-TIDE forecasts **polarity-separated future event structure** with a fully parallel, deterministic network—without iterative sampling, recurrent updates, or large-scale pretraining.

- 🎯 **Motion structure that survives the forecast:** preserves thin boundaries, object contours, and temporally coherent event traces.
- 🚀 **Useful beyond prediction:** forecasted events achieve the strongest downstream segmentation and tracking results in our evaluation.
- 🤖 **Built for latency-critical robotics:** delivers predictable single-pass inference under tight compute and memory budgets.

| ⚡ **Inference Time** | 🧠 **Parameters** | 💾 **VRAM Usage** |
|:---:|:---:|:---:|
| **3.1 ms** | **0.4M** | **0.12 GB** |

## Qualitative Forecasting

<p align="center">
  <img src="https://github.com/user-attachments/assets/c8b1e872-7328-4952-80a4-8d028699e9c5" alt="Qualitative comparison of E-TIDE against E-Motion across multiple forecasting horizons" width="100%" />
</p>

<p align="center">
  <sub><b>Future event prediction across multiple horizons.</b> Given past event frames, E-TIDE preserves object boundaries and motion structure at <i>t+1</i>, <i>t+5</i>, and <i>t+10</i>.</sub>
</p>

## Downstream Perception

<p align="center">
  <img src="https://github.com/user-attachments/assets/1bbefeef-618c-4389-bdc2-812502207009" alt="Downstream perception results using E-TIDE forecasts" width="100%" />
</p>

<p align="center">
  <sub><b>Forecasts that remain useful beyond pixel-level reconstruction.</b> E-TIDE preserves task-relevant structure for downstream event-based perception.</sub>
</p>

## Video Demo

https://github.com/user-attachments/assets/af13cbe7-ce6c-462a-8be7-2e9e8df6d417

<p align="center">
  <sub>Qualitative rollout of future event representations predicted by E-TIDE.</sub>
</p>

## Release Status

- [ ] Training and evaluation code
- [ ] Pretrained checkpoints
- [ ] Data preparation instructions
- [ ] Reproducible benchmark scripts

Code and trained models will be released here.

## Citation

The BibTeX entry will be added when the camera-ready paper is publicly available.
