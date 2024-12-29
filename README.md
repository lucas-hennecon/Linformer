# Linformer: Self-Attention with Linear Complexity

This repository contains an implementation and analysis of the **Linformer** model, a transformer-based architecture designed to reduce the computational cost of self-attention from **O(n²)** to **O(n)**. This project made in collaboration with **Killian Coustoulin** and **Matthieu Neau** applies Linformer to a text classification task using the **IMDB Reviews Dataset** and compares its performance to a standard Transformer. For a detailed presentation of the project and results, refer to the `Linformer.pdf` file.

## 🛠️ Key Features:
- **Transformer and Linformer Models**: Built from scratch, with interchangeable self-attention mechanisms.
- **Task**: Binary classification of movie reviews (positive/negative sentiment) using the IMDB Reviews Dataset.

## 💡 Highlights:
- Linformer achieves comparable accuracy to Transformers while significantly reducing computation time, especially for long sequences.
- Ablation studies performed for different sequence lengths (`n`) and projection dimensions (`k`).

This implementation is based on the original Linformer paper:  
**Linformer: Self-Attention with Linear Complexity**  
*Sinong Wang, Belinda Z. Wei, Dale Schuurmans, Quoc V. Le*  
[arXiv preprint arXiv:2006.04768](https://arxiv.org/abs/2006.04768)
