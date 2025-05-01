# Nexus-Gen：图像理解、生成与编辑的统一模型

发布时间：2025年04月30日

`LLM应用` `多模态模型` `计算机视觉`

> Nexus-Gen: A Unified Model for Image Understanding, Generation, and Editing

# 摘要

> 统一的多模态大型语言模型（MLLMs）致力于通过单一框架整合多模态理解和生成能力。然而，现有开源统一模型在性能上仍与特定领域架构存在差距。为填补这一空白，我们推出了Nexus-Gen，该模型将大型语言模型的语言推理能力与扩散模型的图像合成能力相结合。为了统一大型语言模型与扩散模型的嵌入空间，我们采用了一个双阶段的对齐训练过程。第一阶段，自回归式大型语言模型学习根据多模态输入预测图像嵌入；第二阶段，视觉解码器则训练从这些嵌入中重建高保真度的图像。在训练过程中，我们发现自回归范式在训练与推理阶段之间存在关键性差异，其中连续嵌入空间中的错误累积严重影响了生成质量。为了避免这一问题，我们引入了一种预填充自回归策略，使用带有位置嵌入的特殊令牌预填充输入序列，而非使用连续嵌入。通过双阶段训练，Nexus-Gen已发展出综合处理图像理解、生成和编辑任务的能力。所有模型、数据集和代码均已在https://github.com/modelscope/Nexus-Gen.git上发布，以推动整个领域的进一步发展。

> Unified multimodal large language models (MLLMs) aim to integrate multimodal understanding and generation abilities through a single framework. Despite their versatility, existing open-source unified models exhibit performance gaps against domain-specific architectures. To bridge this gap, we present Nexus-Gen, a unified model that synergizes the language reasoning capabilities of LLMs with the image synthesis power of diffusion models. To align the embedding space of the LLM and diffusion model, we conduct a dual-phase alignment training process. (1) The autoregressive LLM learns to predict image embeddings conditioned on multimodal inputs, while (2) the vision decoder is trained to reconstruct high-fidelity images from these embeddings. During training the LLM, we identified a critical discrepancy between the autoregressive paradigm's training and inference phases, where error accumulation in continuous embedding space severely degrades generation quality. To avoid this issue, we introduce a prefilled autoregression strategy that prefills input sequence with position-embedded special tokens instead of continuous embeddings. Through dual-phase training, Nexus-Gen has developed the integrated capability to comprehensively address the image understanding, generation and editing tasks. All models, datasets, and codes are published at https://github.com/modelscope/Nexus-Gen.git to facilitate further advancements across the field.

[Arxiv](https://arxiv.org/abs/2504.21356)