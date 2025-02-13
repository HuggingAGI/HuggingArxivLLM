# # Top-Theta 注意力机制：利用补偿阈值实现 Transformer 稀疏化

发布时间：2025年02月12日

`LLM理论

论文摘要：注意力机制是Transformer模型的强大核心，但其计算复杂度与序列长度呈二次关系，导致计算开销巨大。我们提出了一种名为Top-Theta注意力（Top-$θ$）的新方法，通过与精心校准的阈值比较，选择性地剪裁不太重要的注意力元素。这种方法在保持模型准确性的同时，显著提升了自注意力矩阵乘法的效率，在生成解码过程中将所需的V缓存行数减少了3倍，并在预填充阶段将注意力元素数量减少了10倍。我们的方法无需重新训练模型，仅需一个简短的校准阶段即可适应分布偏移，因此无需为不同数据集重新校准阈值。与top-k注意力不同，Top-$θ$消除了对全向量的依赖，使其适用于平铺和扩展，避免了昂贵的top-k搜索。我们的关键创新在于开发了高效的数值补偿技术，这些技术在激进剪裁注意力分数时仍能保持模型准确性。` `人工智能`

> Top-Theta Attention: Sparsifying Transformers by Compensated Thresholding

# 摘要

> 注意力机制是Transformer模型的强大核心，但其计算复杂度与序列长度呈二次关系，导致计算开销巨大。我们提出了一种名为Top-Theta注意力（Top-$θ$）的新方法，通过与精心校准的阈值比较，选择性地剪裁不太重要的注意力元素。这种方法在保持模型准确性的同时，显著提升了自注意力矩阵乘法的效率，在生成解码过程中将所需的V缓存行数减少了3倍，并在预填充阶段将注意力元素数量减少了10倍。我们的方法无需重新训练模型，仅需一个简短的校准阶段即可适应分布偏移，因此无需为不同数据集重新校准阈值。与top-k注意力不同，Top-$θ$消除了对全向量的依赖，使其适用于平铺和扩展，避免了昂贵的top-k搜索。我们的关键创新在于开发了高效的数值补偿技术，这些技术在激进剪裁注意力分数时仍能保持模型准确性。

> The attention mechanism is essential for the impressive capabilities of transformer-based Large Language Models (LLMs). However, calculating attention is computationally intensive due to its quadratic dependency on the sequence length. We introduce a novel approach called Top-Theta Attention, or simply Top-$θ$, which selectively prunes less essential attention elements by comparing them against carefully calibrated thresholds. This method greatly improves the efficiency of self-attention matrix multiplication while preserving model accuracy, reducing the number of required V cache rows by 3x during generative decoding and the number of attention elements by 10x during the prefill phase. Our method does not require model retraining; instead, it requires only a brief calibration phase to be resilient to distribution shifts, thus not requiring the thresholds for different datasets to be recalibrated. Unlike top-k attention, Top-$θ$ eliminates full-vector dependency, making it suitable for tiling and scale-out and avoiding costly top-k search. A key innovation of our approach is the development of efficient numerical compensation techniques, which help preserve model accuracy even under aggressive pruning of attention scores.

[Arxiv](https://arxiv.org/abs/2502.08363)