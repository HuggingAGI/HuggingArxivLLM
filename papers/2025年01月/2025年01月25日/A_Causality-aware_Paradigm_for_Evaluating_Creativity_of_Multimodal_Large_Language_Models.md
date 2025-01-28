# 一种因果感知的范式：评估多模态大型语言模型的创造力

发布时间：2025年01月25日

`LLM应用

**理由**：这篇论文主要探讨了如何评估多模态大型语言模型（LLMs）的创造力，并提出了一个名为LoTbench的交互式评估框架。论文的核心在于应用LLMs来解决多模态场景中的创造力评估问题，属于LLM在实际应用中的研究。因此，分类为LLM应用是合适的。` `人工智能` `创造力评估`

> A Causality-aware Paradigm for Evaluating Creativity of Multimodal Large Language Models

# 摘要

> # 摘要
近期，众多基准测试被开发用于评估大型语言模型（LLMs）的逻辑推理能力。然而，由于创造力的主观性、多样性和数据稀缺性，评估LLMs的创造能力颇具挑战，尤其是在多模态场景中。本文探讨了评估多模态LLMs创造力的综合流程，重点关注合适的评估平台和方法。首先，我们引入了Oogiri游戏，这是一个需要幽默、联想思维和对文本、图像或两者产生意外反应的创造力驱动任务。该游戏与现代多模态LLMs的输入输出结构高度契合，并得益于高质量、人类注释的创意响应库，成为研究LLM创造力的理想平台。其次，除了使用Oogiri游戏进行排名和选择等标准评估外，我们提出了LoTbench，一个交互式、因果感知的评估框架，以进一步解决标准评估中的固有风险，如信息泄露和解释性不足。LoTbench不仅更有效地量化了LLM的创造力，还可视化了潜在的创造性思维过程。研究结果表明，尽管大多数LLMs的创造力有限，但LLMs与人类之间的性能差距并非不可逾越。此外，我们发现多模态认知基准MMMU与LoTbench的结果之间存在强相关性，但与传统的创造力指标之间仅有弱相关性。这表明LoTbench更好地与人类认知理论保持一致，强调了认知作为创造力早期阶段的关键基础，并能够桥接不同的概念。https://lotbench.github.io

> Recently, numerous benchmarks have been developed to evaluate the logical reasoning abilities of large language models (LLMs). However, assessing the equally important creative capabilities of LLMs is challenging due to the subjective, diverse, and data-scarce nature of creativity, especially in multimodal scenarios. In this paper, we consider the comprehensive pipeline for evaluating the creativity of multimodal LLMs, with a focus on suitable evaluation platforms and methodologies. First, we find the Oogiri game, a creativity-driven task requiring humor, associative thinking, and the ability to produce unexpected responses to text, images, or both. This game aligns well with the input-output structure of modern multimodal LLMs and benefits from a rich repository of high-quality, human-annotated creative responses, making it an ideal platform for studying LLM creativity. Next, beyond using the Oogiri game for standard evaluations like ranking and selection, we propose LoTbench, an interactive, causality-aware evaluation framework, to further address some intrinsic risks in standard evaluations, such as information leakage and limited interpretability. The proposed LoTbench not only quantifies LLM creativity more effectively but also visualizes the underlying creative thought processes. Our results show that while most LLMs exhibit constrained creativity, the performance gap between LLMs and humans is not insurmountable. Furthermore, we observe a strong correlation between results from the multimodal cognition benchmark MMMU and LoTbench, but only a weak connection with traditional creativity metrics. This suggests that LoTbench better aligns with human cognitive theories, highlighting cognition as a critical foundation in the early stages of creativity and enabling the bridging of diverse concepts. https://lotbench.github.io

[Arxiv](https://arxiv.org/abs/2501.15147)