# Architecture

This repository is a computer-vision research artifact for comparing CNN-based approaches to bottle-defect detection. The Python scripts load an image directory, prepare labels and tensors, construct model variants, train them, and evaluate results.

The research boundary is intentionally separate from production inspection. A production system would require versioned datasets, label-quality controls, deterministic experiment configuration, model and metric tracking, inference validation, hardware and latency testing, monitoring, and a documented human-review path. The committed `__pycache__` artifact should be removed in a future cleanup change.
