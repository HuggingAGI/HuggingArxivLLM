# Robust-LLaVA: 大规模鲁棒图像编码器在多模态大型语言模型中的有效性研究

发布时间：2025年02月03日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在视觉-语言任务中的应用，特别是如何通过对抗性预训练的视觉分类模型来提高MLLMs的鲁棒性。论文的核心在于如何将鲁棒的视觉模型与MLLMs集成，以提升其在复杂推理任务中的表现。这属于LLM在实际应用中的优化和改进，因此归类为LLM应用。` `计算机视觉`

> Robust-LLaVA: On the Effectiveness of Large-Scale Robust Image Encoders for Multi-modal Large Language Models

# 摘要

> # 多模态大型语言模型（MLLMs）在视觉-语言任务中表现出色，但易受视觉对抗性扰动的影响，可能导致幻觉、操纵响应或绕过安全机制。现有方法通过在ImageNet规模数据上对CLIP视觉编码器进行受限的对抗性微调来减轻这些风险，确保其泛化能力得以保留。然而，这种有限的对抗性训练限制了鲁棒性和更广泛的泛化能力。在本研究中，我们探索了一种替代方法，即利用已在大规模数据上进行对抗性预训练的现有视觉分类模型。我们的分析揭示了两个主要贡献：（1）对抗性预训练的广泛规模和多样性使这些模型能够在不需要额外对抗性训练的情况下，对从不可察觉的扰动到高级越狱尝试的各种对抗性威胁表现出卓越的鲁棒性；（2）将这些鲁棒模型与MLLM进行端到端集成，有助于语言组件更好地适应鲁棒的视觉特征，在复杂推理任务中优于现有的即插即用方法。通过对视觉问答、图像描述和越狱攻击的系统评估，我们证明了使用这些鲁棒模型训练的MLLM在保持良好干净性能的同时，实现了卓越的对抗性鲁棒性。我们的框架在描述和VQA任务中分别实现了2倍和1.5倍的平均鲁棒性增益，并在对抗越狱攻击方面提供了超过10%的改进。代码和预训练模型将在https://github.com/HashmatShadab/Robust-LLaVA上提供。

> Multi-modal Large Language Models (MLLMs) excel in vision-language tasks but remain vulnerable to visual adversarial perturbations that can induce hallucinations, manipulate responses, or bypass safety mechanisms. Existing methods seek to mitigate these risks by applying constrained adversarial fine-tuning to CLIP vision encoders on ImageNet-scale data, ensuring their generalization ability is preserved. However, this limited adversarial training restricts robustness and broader generalization. In this work, we explore an alternative approach of leveraging existing vision classification models that have been adversarially pre-trained on large-scale data. Our analysis reveals two principal contributions: (1) the extensive scale and diversity of adversarial pre-training enables these models to demonstrate superior robustness against diverse adversarial threats, ranging from imperceptible perturbations to advanced jailbreaking attempts, without requiring additional adversarial training, and (2) end-to-end MLLM integration with these robust models facilitates enhanced adaptation of language components to robust visual features, outperforming existing plug-and-play methodologies on complex reasoning tasks. Through systematic evaluation across visual question-answering, image captioning, and jail-break attacks, we demonstrate that MLLMs trained with these robust models achieve superior adversarial robustness while maintaining favorable clean performance. Our framework achieves 2x and 1.5x average robustness gains in captioning and VQA tasks, respectively, and delivers over 10% improvement against jailbreak attacks. Code and pretrained models will be available at https://github.com/HashmatShadab/Robust-LLaVA.

[Arxiv](https://arxiv.org/abs/2502.01576)