# 大型语言模型的高维跨语言表示

发布时间：2025年03月14日

`LLM理论` `多语言模型` `跨语言学习`

> High-Dimensional Interlingual Representations of Large Language Models

# 摘要

> 大规模多语言数据集训练的大型语言模型（LLMs）暗示了跨语言构建的形成，即表示空间中共享的子空间。然而，关于这一现象的证据存在矛盾，尚不清楚这些模型是否真正发展出了统一的跨语言表示，还是仅仅呈现出部分对齐的构建。我们研究了31种多样性语言，这些语言在资源级别、类型学和地理区域上各不相同，发现多语言LLMs在跨语言对齐方面表现不一致。为了解决这一问题，我们提出了一种跨语言表示框架，用于识别共享的跨语言语义子空间以及由于表示限制而存在的碎片化组件。我们引入了跨语言局部重叠（ILO）分数，通过比较高维表示的局部邻域结构来量化跨语言对齐。我们利用ILO来研究单语言微调对多语言LLMs中跨语言表示的影响。我们的结果显示，仅在单语言上进行训练会破坏早期层的对齐，而冻结这些层则可以保持跨语言表示的对齐，从而提高跨语言泛化能力。这些结果验证了我们的框架和评估跨语言表示的指标，并进一步强调了跨语言对齐对于可扩展的多语言学习至关重要。

> Large language models (LLMs) trained on massive multilingual datasets hint at the formation of interlingual constructs--a shared subspace in the representation space. However, evidence regarding this phenomenon is mixed, leaving it unclear whether these models truly develop unified interlingual representations, or present a partially aligned constructs. We explore 31 diverse languages varying on their resource-levels, typologies, and geographical regions; and find that multilingual LLMs exhibit inconsistent cross-lingual alignments. To address this, we propose an interlingual representation framework identifying both the shared interlingual semantic subspace and fragmented components, existed due to representational limitations. We introduce Interlingual Local Overlap (ILO) score to quantify interlingual alignment by comparing the local neighborhood structures of high-dimensional representations. We utilize ILO to investigate the impact of single-language fine-tuning on the interlingual representations in multilingual LLMs. Our results indicate that training exclusively on a single language disrupts the alignment in early layers, while freezing these layers preserves the alignment of interlingual representations, leading to improved cross-lingual generalization. These results validate our framework and metric for evaluating interlingual representation, and further underscore that interlingual alignment is crucial for scalable multilingual learning.

[Arxiv](https://arxiv.org/abs/2503.11280)