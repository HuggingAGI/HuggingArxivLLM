# # AdvSumm：对抗训练助力文本摘要偏差缓解：AdvSumm方法解析

发布时间：2025年06月06日

`LLM应用` `文本摘要` `机器学习`

> AdvSumm: Adversarial Training for Bias Mitigation in Text Summarization

# 摘要

> 大型语言模型（LLMs）在文本摘要领域表现优异，并逐渐成为现实应用中的重要工具。然而，这些模型往往继承了预训练数据中的联想和框架偏见，导致下游任务中可能出现不恰当或不公平的结果。为此，我们提出了AdvSumm（对抗性摘要），一个通用领域的训练框架，旨在通过提升模型的泛化能力来减少文本摘要中的偏见问题。受对抗鲁棒性启发，AdvSumm创新性地引入了一个Perturber组件，该组件通过在序列到序列模型的嵌入层施加梯度引导的扰动，增强了模型对输入变化的鲁棒性。实验证明，AdvSumm能够有效减少摘要中的多种偏见，特别是姓名-国籍偏见和政治框架偏见，同时保持摘要质量不受影响。与标准Transformer模型和回译等数据增强技术相比，AdvSumm在多个基准数据集上展现了更出色的偏见缓解效果。

> Large Language Models (LLMs) have achieved impressive performance in text summarization and are increasingly deployed in real-world applications. However, these systems often inherit associative and framing biases from pre-training data, leading to inappropriate or unfair outputs in downstream tasks. In this work, we present AdvSumm (Adversarial Summarization), a domain-agnostic training framework designed to mitigate bias in text summarization through improved generalization. Inspired by adversarial robustness, AdvSumm introduces a novel Perturber component that applies gradient-guided perturbations at the embedding level of Sequence-to-Sequence models, enhancing the model's robustness to input variations. We empirically demonstrate that AdvSumm effectively reduces different types of bias in summarization-specifically, name-nationality bias and political framing bias-without compromising summarization quality. Compared to standard transformers and data augmentation techniques like back-translation, AdvSumm achieves stronger bias mitigation performance across benchmark datasets.

[Arxiv](https://arxiv.org/abs/2506.06273)