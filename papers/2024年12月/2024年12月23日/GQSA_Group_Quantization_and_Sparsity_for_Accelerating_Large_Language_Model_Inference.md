# GQSA：旨在加速大型语言模型推理的分组量化与稀疏性

发布时间：2024年12月23日

`LLM应用` `模型压缩` `大型语言模型`

> GQSA: Group Quantization and Sparsity for Accelerating Large Language Model Inference

# 摘要

> 随着大型语言模型（LLMs）规模与复杂性的迅猛增长，训练和推理的成本大幅上扬。模型压缩已成为降低内存使用和计算开销的主流办法。本文呈现了一种专为LLMs打造的新型压缩技术——组量化和稀疏加速（	extbf{GQSA}）。传统方法通常仅聚焦于量化或者稀疏化，然而依赖单一策略在高压缩率时往往会造成显著的性能损失。相较而言，GQSA将量化和稀疏化紧密结合，借助对GPU友好的结构化组稀疏性和量化来实现高效加速。所提出的方法涵盖三个关键步骤。首先，GQSA运用组结构化剪枝来遵循对GPU友好的稀疏模式约束。其次，采用两阶段的稀疏感知训练流程，在压缩后最大程度地保留性能。最后，该框架采用块稀疏行（BSR）格式，以达成实际部署和高效执行。在LLaMA模型家族上的实验结果显示，GQSA在模型速度和准确性之间达成了绝佳的平衡。此外，在最新的LLaMA-3和LLaMA-3.1模型上，GQSA显著优于现有的LLM压缩技术。

> With the rapid growth in the scale and complexity of large language models (LLMs), the costs of training and inference have risen substantially. Model compression has emerged as a mainstream solution to reduce memory usage and computational overhead. This paper presents Group Quantization and Sparse Acceleration (\textbf{GQSA}), a novel compression technique tailored for LLMs. Traditional methods typically focus exclusively on either quantization or sparsification, but relying on a single strategy often results in significant performance loss at high compression rates. In contrast, GQSA integrates quantization and sparsification in a tightly coupled manner, leveraging GPU-friendly structured group sparsity and quantization for efficient acceleration. The proposed method consists of three key steps. First, GQSA applies group structured pruning to adhere to GPU-friendly sparse pattern constraints. Second, a two-stage sparsity-aware training process is employed to maximize performance retention after compression. Finally, the framework adopts the Block Sparse Row (BSR) format to enable practical deployment and efficient execution. Experimental results on the LLaMA model family show that GQSA achieves an excellent balance between model speed and accuracy. Furthermore, on the latest LLaMA-3 and LLaMA-3.1 models, GQSA outperforms existing LLM compression techniques significantly.

[Arxiv](https://arxiv.org/abs/2412.17560)