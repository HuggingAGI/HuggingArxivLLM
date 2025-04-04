# 探索通用且鲁棒的基于LLM的文本增强图学习

发布时间：2025年04月03日

`LLM应用` `图神经网络` `文本分析`

> Toward General and Robust LLM-enhanced Text-attributed Graph Learning

# 摘要

> 大型语言模型（LLMs）的突破性进展与文本属性图（TAGs）在各领域的广泛应用，使增强型TAG学习成为了一个备受关注的研究方向。通过充分利用图结构的丰富描述信息，这一范式借助LLMs生成高质量的嵌入表示，从而显著提升了图神经网络（GNNs）的表达能力。然而，该领域仍面临两大挑战：其一，缺乏一个统一的框架来系统化LLMs与GNNs之间复杂交互所引发的多样化优化视角；其二，缺乏一种稳健的方法来处理现实世界中TAGs的文本和边稀疏性问题，这往往导致性能不佳。

为应对这些挑战，我们提出了UltraTAG，一个LLM增强型TAG学习的统一框架。UltraTAG不仅提供了一个全面且领域自适应的统一框架，整合现有方法，更为该领域的未来进展奠定了基础。基于此框架，我们进一步提出了UltraTAG-S，它是UltraTAG的一个稳健实现，专为解决现实世界TAGs中的固有稀疏性问题而设计。UltraTAG-S采用基于LLM的文本传播和文本增强来缓解文本稀疏性，同时利用基于PageRank的LLM增强节点选择技术和边重构策略来解决边稀疏性问题。通过广泛的实验验证，UltraTAG-S在理想和稀疏设置下分别实现了2.12%和17.47%的性能提升，显著超越了现有基线。此外，随着数据稀疏性比率的增加，UltraTAG-S的性能提升也相应增加，这充分证明了其有效性和稳健性。


> Recent advancements in Large Language Models (LLMs) and the proliferation of Text-Attributed Graphs (TAGs) across various domains have positioned LLM-enhanced TAG learning as a critical research area. By utilizing rich graph descriptions, this paradigm leverages LLMs to generate high-quality embeddings, thereby enhancing the representational capacity of Graph Neural Networks (GNNs). However, the field faces significant challenges: (1) the absence of a unified framework to systematize the diverse optimization perspectives arising from the complex interactions between LLMs and GNNs, and (2) the lack of a robust method capable of handling real-world TAGs, which often suffer from texts and edge sparsity, leading to suboptimal performance.
  To address these challenges, we propose UltraTAG, a unified pipeline for LLM-enhanced TAG learning. UltraTAG provides a unified comprehensive and domain-adaptive framework that not only organizes existing methodologies but also paves the way for future advancements in the field. Building on this framework, we propose UltraTAG-S, a robust instantiation of UltraTAG designed to tackle the inherent sparsity issues in real-world TAGs. UltraTAG-S employs LLM-based text propagation and text augmentation to mitigate text sparsity, while leveraging LLM-augmented node selection techniques based on PageRank and edge reconfiguration strategies to address edge sparsity. Our extensive experiments demonstrate that UltraTAG-S significantly outperforms existing baselines, achieving improvements of 2.12\% and 17.47\% in ideal and sparse settings, respectively. Moreover, as the data sparsity ratio increases, the performance improvement of UltraTAG-S also rises, which underscores the effectiveness and robustness of UltraTAG-S.

[Arxiv](https://arxiv.org/abs/2504.02343)