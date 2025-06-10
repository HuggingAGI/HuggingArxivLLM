# # 缓解多模态大语言模型在序列图像中的幻觉行为
探索如何有效缓解多模态大语言模型在处理序列图像时的幻觉行为。

发布时间：2025年06月08日

`LLM应用` `智能助手` `内容生成`

> Mitigating Behavioral Hallucination in Multimodal Large Language Models for Sequential Images

# 摘要

> 多模态大型语言模型在多种任务中表现出色，但幻觉问题仍然是其可靠性和可扩展性的瓶颈。当前研究主要针对客观幻觉，但对于连续图像，行为幻觉这一现象的研究仍显不足。本研究旨在填补这一空白。我们发现，行为幻觉主要由先验驱动的偏见和滚雪球效应引发。为此，我们提出了SHE（Sequence Hallucination Eradication），一个轻量级的两阶段框架：首先通过自适应时间窗口的视觉-文本对齐检查检测幻觉，然后通过正交投影到联合嵌入空间来缓解幻觉。我们还引入了BEACH指标，用于量化行为幻觉的严重程度。实验结果表明，SHE在保持描述准确性的同时，将行为幻觉减少了10%以上的BEACH分数。

> While multimodal large language models excel at various tasks, they still suffer from hallucinations, which limit their reliability and scalability for broader domain applications. To address this issue, recent research mainly focuses on objective hallucination. However, for sequential images, besides objective hallucination, there is also behavioral hallucination, which is less studied. This work aims to fill in the gap. We first reveal that behavioral hallucinations mainly arise from two key factors: prior-driven bias and the snowball effect. Based on these observations, we introduce SHE (Sequence Hallucination Eradication), a lightweight, two-stage framework that (1) detects hallucinations via visual-textual alignment check using our proposed adaptive temporal window and (2) mitigates them via orthogonal projection onto the joint embedding space. We also propose a new metric (BEACH) to quantify behavioral hallucination severity. Empirical results on standard benchmarks demonstrate that SHE reduces behavioral hallucination by over 10% on BEACH while maintaining descriptive accuracy.

[Arxiv](https://arxiv.org/abs/2506.07184)