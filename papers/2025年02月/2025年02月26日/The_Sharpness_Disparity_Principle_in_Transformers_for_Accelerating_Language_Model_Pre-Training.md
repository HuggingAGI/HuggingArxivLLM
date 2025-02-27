# Transformer模型中的锐度差异原理：加速语言模型预训练的新方法

发布时间：2025年02月26日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）训练过程中的模块间差异和优化策略，属于模型训练的理论研究，因此归类为LLM理论。` `机器学习`

> The Sharpness Disparity Principle in Transformers for Accelerating Language Model Pre-Training

# 摘要

> 变换器模型由嵌入层、归一化层、自注意力机制和点式前馈网络等多种模块组成。理解这些模块的差异与交互至关重要。本文发现，这些模块之间存在显著的“Sharpness Disparity”（尖锐度差异），这种差异在训练初期出现，并贯穿整个训练过程。基于这一发现，我们提出了“分块学习率”（Blockwise Learning Rate）策略，根据各模块的尖锐度调整学习率，从而加速大型语言模型（LLM）的预训练。通过将Blockwise LR与AdamW结合，我们实现了更低的终端损失，并较原始AdamW训练速度提升近2倍。我们在GPT-2和LLaMA模型上验证了这一加速效果，模型规模从0.12B到1.1B，数据集涵盖OpenWebText和MiniPile。最后，我们将Blockwise LR与近期提出的内存高效Adam变体Adam-mini（Zhang et al., 2024）结合，实现了2倍的速度提升和内存节省。这些结果表明，利用模块间尖锐度差异提升LLM训练具有巨大潜力。

> Transformers consist of diverse building blocks, such as embedding layers, normalization layers, self-attention mechanisms, and point-wise feedforward networks. Thus, understanding the differences and interactions among these blocks is important. In this paper, we uncover a clear Sharpness Disparity across these blocks, which emerges early in training and intriguingly persists throughout the training process. Motivated by this finding, we propose Blockwise Learning Rate (LR), a strategy that tailors the LR to each block's sharpness, accelerating large language model (LLM) pre-training. By integrating Blockwise LR into AdamW, we consistently achieve lower terminal loss and nearly $2\times$ speedup compared to vanilla AdamW. We demonstrate this acceleration across GPT-2 and LLaMA, with model sizes ranging from 0.12B to 1.1B and datasets of OpenWebText and MiniPile. Finally, we incorporate Blockwise LR into Adam-mini (Zhang et al., 2024), a recently proposed memory-efficient variant of Adam, achieving a combined $2\times$ speedup and $2\times$ memory saving. These results underscore the potential of exploiting the sharpness disparity to improve LLM training.

[Arxiv](https://arxiv.org/abs/2502.19002)