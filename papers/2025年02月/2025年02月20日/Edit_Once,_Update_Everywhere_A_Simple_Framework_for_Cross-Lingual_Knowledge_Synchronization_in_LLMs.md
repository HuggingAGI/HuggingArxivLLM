# 一处编辑，处处更新——大型语言模型的跨语言知识同步新框架

发布时间：2025年02月20日

`LLM应用` `人工智能`

> Edit Once, Update Everywhere: A Simple Framework for Cross-Lingual Knowledge Synchronization in LLMs

# 摘要

> 知识编辑让大型语言模型能够快速适应新信息或更正，无需重新训练。然而，现有方法多局限于单一语言或基础多语言编辑，难以实现真正的跨语言知识同步。为解决这一问题，我们提出了一种简单实用的最新方法——跨语言知识民主化编辑（X-KDE），旨在将主导语言的知识高效传递到其他语言。我们的X-KDE包含两个阶段：（i）跨语言编辑指令微调（XE-IT），通过在精选的平行数据集上微调模型，实现知识的精准修改，同时保留不相关信息；（ii）目标语言偏好优化（TL-PO），利用高级优化技术确保语言间的一致性，促进跨语言更新的传递。此外，我们还构建了一个高质量的跨语言数据集，专为增强跨语言知识转移而设计。在Bi-ZsRE和MzsRE基准上的实验表明，X-KDE显著提升了跨语言性能，平均提升+8.19%，同时在单语言设置中保持了高精度。

> Knowledge editing allows for efficient adaptation of large language models (LLMs) to new information or corrections without requiring full retraining. However, prior methods typically focus on either single-language editing or basic multilingual editing, failing to achieve true cross-linguistic knowledge synchronization. To address this, we present a simple and practical state-of-the-art (SOTA) recipe Cross-Lingual Knowledge Democracy Edit (X-KDE), designed to propagate knowledge from a dominant language to other languages effectively. Our X-KDE comprises two stages: (i) Cross-lingual Edition Instruction Tuning (XE-IT), which fine-tunes the model on a curated parallel dataset to modify in-scope knowledge while preserving unrelated information, and (ii) Target-language Preference Optimization (TL-PO), which applies advanced optimization techniques to ensure consistency across languages, fostering the transfer of updates. Additionally, we contribute a high-quality, cross-lingual dataset, specifically designed to enhance knowledge transfer across languages. Extensive experiments on the Bi-ZsRE and MzsRE benchmarks show that X-KDE significantly enhances cross-lingual performance, achieving an average improvement of +8.19%, while maintaining high accuracy in monolingual settings.

[Arxiv](https://arxiv.org/abs/2502.14645)