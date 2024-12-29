# Linformer: Self-Attention with Linear Complexity

This repository contains an implementation and analysis of the **Linformer** model, a transformer-based architecture designed to reduce the computational cost of self-attention from **O(n²)** to **O(n)**. This project made in collaboration with **Killian Coustoulin** and **Matthieu Neau** applies Linformer to a text classification task using the **IMDB Reviews Dataset** and compares its performance to a standard Transformer.

### Key Features:
- **Transformer and Linformer Models**: Built from scratch, with interchangeable self-attention mechanisms.
- **Projection Strategies**:
  - Headwise Sharing
  - Layerwise Sharing
  - Single and Dual Projections
- **Task**: Binary classification of movie reviews (positive/negative sentiment) using the IMDB Reviews Dataset.

### Highlights:
- Linformer achieves comparable accuracy to Transformers while significantly reducing computation time, especially for long sequences.
- Ablation studies performed for different sequence lengths (`n`) and projection dimensions (`k`).
