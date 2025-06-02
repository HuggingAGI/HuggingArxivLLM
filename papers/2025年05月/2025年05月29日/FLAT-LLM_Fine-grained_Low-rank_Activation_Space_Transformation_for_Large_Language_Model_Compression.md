# FLAT-LLM：用于大规模语言模型压缩的细粒度低秩激活空间变换

发布时间：2025年05月29日

`LLM应用` `模型压缩`

> FLAT-LLM: Fine-grained Low-rank Activation Space Transformation for Large Language Model Compression

# 摘要

> 大型语言模型（LLMs）推动了自然语言处理领域的显著进步，但其高计算和内存需求为资源受限环境中的部署带来了挑战。尽管低秩分解方法为结构压缩提供了有前景的途径，但它们常面临准确性下降、昂贵的校准过程以及导致低效模型架构的问题，这些阻碍了实际推理速度的提升。本文提出了一种名为FLAT-LLM的快速且精确的无训练结构压缩方法，该方法基于激活空间中的细粒度低秩变换。具体而言，我们通过基于头部的主成分分析（PCA）计算出的截断特征向量来变换权重，从而减少隐层维度，并采用基于重要性的指标在解码器之间自适应分配秩。FLAT-LLM无需恢复微调即可实现高效且有效的权重压缩，校准过程可在几分钟内完成。在4个模型和11个数据集上的评估表明，FLAT-LLM在泛化能力和下游性能上优于结构剪枝基线，同时在分解方法的基础上实现了推理加速。

> Large Language Models (LLMs) have enabled remarkable progress in natural language processing, yet their high computational and memory demands pose challenges for deployment in resource-constrained environments. Although recent low-rank decomposition methods offer a promising path for structural compression, they often suffer from accuracy degradation, expensive calibration procedures, and result in inefficient model architectures that hinder real-world inference speedups. In this paper, we propose FLAT-LLM, a fast and accurate, training-free structural compression method based on fine-grained low-rank transformations in the activation space. Specifically, we reduce the hidden dimension by transforming the weights using truncated eigenvectors computed via head-wise Principal Component Analysis (PCA), and employ an importance-based metric to adaptively allocate ranks across decoders. FLAT-LLM achieves efficient and effective weight compression without recovery fine-tuning, which could complete the calibration within a few minutes. Evaluated across 4 models and 11 datasets, FLAT-LLM outperforms structural pruning baselines in generalization and downstream performance, while delivering inference speedups over decomposition-based methods.

[Arxiv](https://arxiv.org/abs/2505.23966)