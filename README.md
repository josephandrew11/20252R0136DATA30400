# 20252R0136DATA30400
A project for hierarchical multi-label text classification of product reviews.

> # 🏆 Best Score Reproduction

> Run `10_coreclass_mlp_gat_selftrain_EMA_modified_dynamic_topk.ipynb` to reproduce the best Kaggle F1 score achieved in this project (0.53311 on AWS, 0.53470 on Colab).
This notebook implements the final taxonomy-aware pipeline, which combines an MLP document encoder, GAT-based label encoding over the taxonomy, EMA-stabilized self-training, and a dynamic top-k (2–3) prediction strategy validated.



> The `embeddings/` directory contains precomputed document and label embeddings generated using `alibaba-nlp/gte-base-en-v1.5`.