# ML Projects 🧠🔮

This directory contains two independent machine learning projects that share no codebase or tooling.

## [ml-gnn/](ml-gnn/) — Graph Convolutional Networks for Security Infrastructure 🕸️

Applies GCN deep learning methods to security infrastructure analysis. Includes:

- **Collection module** (`src/collection/`): Ingests Terraform workspace data, converts HCL digraphs into structured datasets (DOT, PNG, JSON) for GNN training
- **Training pipeline** (`src/training/`): Model training with TensorFlow/Keras backend
- **Visualization** (`src/visualize/`): Graph visualization tools (Gephi, Docker-based Rover)
- **Research paper** (`docs/paper/`): Full analysis and optimization paper (LaTeX source + PDF)
- **Dataset management**: DVC-tracked data files — only `.dvc` pointers are committed

See [ml-gnn/README.md](ml-gnn/README.md) for setup instructions.

## [model-html/](model-html/) — SAEPIO & Kaggle Dataset Ingestion 👻

Tests automated HTML dataset pipelines:

- SAEPIO data import (OSINT services, header analysis)
- Kaggle dataset ingestion with secure API key management
- CML-based GitHub Actions for training models in CI
- Aeonium autoencoder network implementations (SAEIO)

See [model-html/README.md](model-html/README.md) for details.

---

⛧ Draft by **n0ctilucent** | [bitsmasher.net/research](https://www.bitsmasher.net/research/)