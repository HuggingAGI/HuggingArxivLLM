# MilChat：专为遥感领域设计的多模态小语言模型，首次引入链式思维推理与GRPO

发布时间：2025年05月12日

`LLM应用

摘要中讨论了多模态大语言模型（MLLMs）在特定领域的应用，特别是通过构建新数据集、监督微调和强化学习来优化模型在偏远地区遥感图像分析中的性能。这些工作属于模型的应用和优化，因此归类为LLM应用。`

> MilChat: Introducing Chain of Thought Reasoning and GRPO to a Multimodal Small Language Model for Remote Sensing

# 摘要

> 多模态大语言模型（MLLMs）在文本与图像内容的理解与生成方面展现出卓越能力。然而，这些模型在特定领域，尤其是需要资源高效且领域专属适应的场景中，表现仍有待提升。为此，我们推出了一款轻量级多模态语言模型MilChat，专门针对偏远地区的遥感图像分析进行优化，包括导弹发射场等极具挑战性的场景。我们通过专家审核验证了数百张航空图像，构建了一个全新的数据集MilData，并通过详细标注突出了微妙的军事设施。通过对一个20亿参数的开源MLLM进行监督微调，并结合链式思维（CoT）推理标注，模型能够提供更准确且易于理解的解释。此外，我们引入了组相对策略优化（GRPO），以增强模型对关键领域特定线索（如防御布局和重要军事结构）的检测能力，同时显著降低了对民用场景的误报率。实证评估表明，MilChat在开放式的图像描述和分类指标上，显著超越了现有的大型通用多模态模型和专门针对遥感适应的方法。在新提出的MilData基准测试中，模型实现了超过80%的召回率和98%的精确率，充分证明了针对性微调和强化学习在专业实际应用中的强大潜力。

> Remarkable capabilities in understanding and generating text-image content have been demonstrated by recent advancements in multimodal large language models (MLLMs). However, their effectiveness in specialized domains-particularly those requiring resource-efficient and domain-specific adaptations-has remained limited. In this work, a lightweight multimodal language model termed MilChat is introduced, specifically adapted to analyze remote sensing imagery in secluded areas, including challenging missile launch sites. A new dataset, MilData, was compiled by verifying hundreds of aerial images through expert review, and subtle military installations were highlighted via detailed captions. Supervised fine-tuning on a 2B-parameter open-source MLLM with chain-of-thought (CoT) reasoning annotations was performed, enabling more accurate and interpretable explanations. Additionally, Group Relative Policy Optimization (GRPO) was leveraged to enhance the model's ability to detect critical domain-specific cues-such as defensive layouts and key military structures-while minimizing false positives on civilian scenes. Through empirical evaluations, it has been shown that MilChat significantly outperforms both larger, general-purpose multimodal models and existing remote sensing-adapted approaches on open-ended captioning and classification metrics. Over 80% recall and 98% precision were achieved on the newly proposed MilData benchmark, underscoring the potency of targeted fine-tuning and reinforcement learning in specialized real-world applications.

[Arxiv](https://arxiv.org/abs/2505.07984)