# 哨兵：抵御提示注入的最新一代模型

发布时间：2025年06月05日

`LLM应用` `网络安全`

> Sentinel: SOTA model to protect against prompt injections

# 摘要

> 大型语言模型（LLMs）虽然日益强大，但依然面临提示注入攻击的威胁，这类攻击通过恶意输入使模型偏离预期指令。本文推出了一种创新的检测模型Sentinel，基于nswerdotai/ModernBERT-large架构。借助ModernBERT的先进特性，并在包含开源与私有集合的多样化数据集上进行微调，Sentinel达到了顶尖的性能水平。该数据集涵盖了从角色扮演、指令劫持到生成有偏见内容等多种攻击类型，同时整合了广泛的良性指令，其中私有数据特别针对细微错误修正和现实误分类问题。在全面的内部测试集上，Sentinel实现了0.987的平均准确率和0.980的F1分数。此外，在公共基准测试中，它显著超越了protectai/deberta-v3-base-prompt-injection-v2等强劲基线模型。本文详述了Sentinel的架构、数据集构建、训练方法及全面评估，彰显其卓越的检测能力。

> Large Language Models (LLMs) are increasingly powerful but remain vulnerable to prompt injection attacks, where malicious inputs cause the model to deviate from its intended instructions. This paper introduces Sentinel, a novel detection model, qualifire/prompt-injection-sentinel, based on the \answerdotai/ModernBERT-large architecture. By leveraging ModernBERT's advanced features and fine-tuning on an extensive and diverse dataset comprising a few open-source and private collections, Sentinel achieves state-of-the-art performance. This dataset amalgamates varied attack types, from role-playing and instruction hijacking to attempts to generate biased content, alongside a broad spectrum of benign instructions, with private datasets specifically targeting nuanced error correction and real-world misclassifications. On a comprehensive, unseen internal test set, Sentinel demonstrates an average accuracy of 0.987 and an F1-score of 0.980. Furthermore, when evaluated on public benchmarks, it consistently outperforms strong baselines like protectai/deberta-v3-base-prompt-injection-v2. This work details Sentinel's architecture, its meticulous dataset curation, its training methodology, and a thorough evaluation, highlighting its superior detection capabilities.

[Arxiv](https://arxiv.org/abs/2506.05446)