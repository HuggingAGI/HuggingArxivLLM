# SAISA：兼具训练与推理效率的多模态大语言模型

发布时间：2025年02月04日

`LLM理论

**理由**：这篇论文主要探讨了多模态大型语言模型（MLLMs）的架构设计，特别是视觉标记的注意力机制，并提出了一种新的自注意力机制NAAViT和新的架构SAISA。这些研究内容属于对大型语言模型的理论改进和优化，因此应归类为LLM理论。` `计算机视觉`

> SAISA: Towards Multimodal Large Language Models with Both Training and Inference Efficiency

# 摘要

> # 多模态大型语言模型（MLLMs）主要有两种架构，每种架构在训练和推理效率上各有优劣：嵌入空间对齐（如LLaVA-1.5）在推理时效率较低，而交叉注意力空间对齐（如Flamingo）在训练时效率较低。本文比较了这两种架构，并探讨了构建高效MLLMs的关键因素。两者的主要区别在于视觉标记的注意力机制，尤其是它们之间的交互方式。为了验证视觉标记间的注意力是否必要，我们提出了一种新的自注意力机制——NAAViT（	extbf{N}o 	extbf{A}ttention 	extbf{A}mong 	extbf{Vi}sual 	extbf{T}okens），它移除了视觉标记间的注意力。我们在LLaVA-1.5上的初步实验表明，视觉标记间的注意力高度冗余。基于这一发现，我们提出了SAISA（	extbf{S}elf-	extbf{A}ttention 	extbf{I}nput 	extbf{S}pace 	extbf{A}lignment），这一新架构显著提升了训练和推理效率。SAISA将视觉特征直接与NAAViT自注意力块的输入空间对齐，减少了自注意力块和前馈网络（FFNs）的计算开销。在相同配置下，SAISA将推理FLOPs降低了66\%，训练预算减少了26\%，同时在准确性上表现更优。全面的消融实验进一步验证了SAISA在不同LLMs和视觉编码器中的有效性。代码和模型将在https://github.com/icip-cas/SAISA上开源。

> Multimodal Large Language Models (MLLMs) mainly fall into two architectures, each involving a trade-off between training and inference efficiency: embedding space alignment (e.g., LLaVA-1.5) is inefficient during inference, while cross-attention space alignment (e.g., Flamingo) is inefficient in training. In this paper, we compare these two architectures and identify the key factors for building efficient MLLMs. A primary difference between them lies in how attention is applied to visual tokens, particularly in their interactions with each other. To investigate whether attention among visual tokens is necessary, we propose a new self-attention mechanism, NAAViT (\textbf{N}o \textbf{A}ttention \textbf{A}mong \textbf{Vi}sual \textbf{T}okens), which eliminates this type of attention. Our pilot experiment on LLaVA-1.5 shows that attention among visual tokens is highly redundant. Based on these insights, we introduce SAISA (\textbf{S}elf-\textbf{A}ttention \textbf{I}nput \textbf{S}pace \textbf{A}lignment), a novel architecture that enhance both training and inference efficiency. SAISA directly aligns visual features with the input spaces of NAAViT self-attention blocks, reducing computational overhead in both self-attention blocks and feed-forward networks (FFNs). Using the same configuration as LLaVA-1.5, SAISA reduces inference FLOPs by 66\% and training budget by 26\%, while achieving superior performance in terms of accuracy. Comprehensive ablation studies further validate the effectiveness of SAISA across various LLMs and visual encoders. The code and model will be publicly available at https://github.com/icip-cas/SAISA.

[Arxiv](https://arxiv.org/abs/2502.02458)