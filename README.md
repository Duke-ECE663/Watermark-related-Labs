# Watermark-related Labs

This repository collects two labs on image watermarking for AI-generated content: one studies **attacks** on watermark-based detectors, and the other studies **defenses** with certified robustness guarantees.

## Labs

### [lab1](lab1) — WEvade (Attack)

Official implementation of *Evading Watermark based Detection of AI-Generated Content* (CCS 2023).

WEvade evaluates how well adversaries can evade watermark-based detection of AI-generated images. It includes white-box attacks (WEvade-W) and query-based black-box attacks (WEvade-B-Q) against learned image watermarks.

- Paper: [arXiv:2305.03807](https://arxiv.org/abs/2305.03807)

### [lab2](lab2) — Certifiably Robust Image Watermark (Defense)

Official implementation of *Certifiably Robust Image Watermark* (ECCV 2024).

This lab implements randomized-smoothing-based watermark detectors and tools to evaluate their **certified robustness** against bounded perturbations (e.g., under different training strategies, detection thresholds, and noise levels).

- Paper: [arXiv:2407.04086](https://arxiv.org/abs/2407.04086)

## Getting started

Each lab is included as a git submodule. After cloning this repository, initialize submodules:

```bash
git clone --recurse-submodules https://github.com/Duke-ECE663/Watermark-related-Labs.git
# or, if already cloned:
git submodule update --init --recursive
```

See each lab’s README for environment setup and run instructions.
