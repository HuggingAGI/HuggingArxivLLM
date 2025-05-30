# 机器遗忘是否真的移除了模型知识？一个用于审计大语言模型去学习的框架

发布时间：2025年05月29日

`LLM理论` `数据隐私` `版权保护`

> Does Machine Unlearning Truly Remove Model Knowledge? A Framework for Auditing Unlearning in LLMs

# 摘要

> 近年来，大型语言模型（LLMs）取得了显著进展，吸引了研究界的广泛关注。其能力主要归功于大型架构，这些架构需要在海量数据集上进行大量训练。然而，这些数据集通常包含来自公共互联网的敏感或受版权保护的内容，引发关于数据隐私和所有权的担忧。《通用数据保护条例》（GDPR）等法规赋予个人要求删除此类敏感信息的权利。这推动了机器遗忘算法的发展，旨在无需昂贵的重新训练即可从模型中移除特定知识。尽管取得了这些进展，但评估遗忘算法的有效性仍然具有挑战性，这是由于LLMs固有的复杂性和生成性。在本研究中，我们引入了一个全面的遗忘评估框架，包含三个基准数据集、六种遗忘算法和五种基于提示的审计方法。通过使用各种审计算法，我们评估了不同遗忘策略的有效性和鲁棒性。为了探索基于提示审计之外的替代方案，我们提出了一种利用中间激活扰动的新技术，解决了仅依赖模型输入和输出的审计方法的局限性。

> In recent years, Large Language Models (LLMs) have achieved remarkable advancements, drawing significant attention from the research community. Their capabilities are largely attributed to large-scale architectures, which require extensive training on massive datasets. However, such datasets often contain sensitive or copyrighted content sourced from the public internet, raising concerns about data privacy and ownership. Regulatory frameworks, such as the General Data Protection Regulation (GDPR), grant individuals the right to request the removal of such sensitive information. This has motivated the development of machine unlearning algorithms that aim to remove specific knowledge from models without the need for costly retraining. Despite these advancements, evaluating the efficacy of unlearning algorithms remains a challenge due to the inherent complexity and generative nature of LLMs. In this work, we introduce a comprehensive auditing framework for unlearning evaluation, comprising three benchmark datasets, six unlearning algorithms, and five prompt-based auditing methods. By using various auditing algorithms, we evaluate the effectiveness and robustness of different unlearning strategies. To explore alternatives beyond prompt-based auditing, we propose a novel technique that leverages intermediate activation perturbations, addressing the limitations of auditing methods that rely solely on model inputs and outputs.

[Arxiv](https://arxiv.org/abs/2505.23270)