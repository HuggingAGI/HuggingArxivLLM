# Mordal: 视觉语言模型的自动化预训练模型选择

发布时间：2025年01月31日

`LLM应用

**解释**：这篇论文主要讨论了如何将多模态（如视觉）融入大型语言模型（LLMs），并提出了一个自动化框架（Mordal）来优化视觉语言模型（VLMs）的搜索和评估过程。虽然涉及多模态和自动化框架，但其核心仍然是围绕如何提升和应用LLMs的能力，因此归类为“LLM应用”。` `机器人`

> Mordal: Automated Pretrained Model Selection for Vision Language Models

# 摘要

> 将多模态融入大型语言模型（LLMs）是提升其理解非文本数据能力的有效途径，使其能够执行多模态任务。视觉语言模型（VLMs）因其在医疗、机器人和无障碍等领域的广泛应用，成为多模态模型中增长最快的类别。然而，尽管现有VLMs在各类基准测试中展现了卓越的视觉能力，但它们仍依赖人工设计，缺乏自动化框架来构建特定任务的多模态模型。
    我们推出了Mordal，一个自动化多模态模型搜索框架，能够高效地为用户定义的任务找到最佳VLM，无需人工干预。Mordal通过减少搜索过程中的候选模型数量，并缩短评估时间，实现了这一目标。评估结果显示，Mordal在寻找最佳VLM时，GPU使用时间比网格搜索减少了$8.9	imes$--$11.6	imes$。此外，我们还发现了一些新的VLMs，它们在性能上超越了现有的最先进模型。

> Incorporating multiple modalities into large language models (LLMs) is a powerful way to enhance their understanding of non-textual data, enabling them to perform multimodal tasks. Vision language models (VLMs) form the fastest growing category of multimodal models because of their many practical use cases, including in healthcare, robotics, and accessibility. Unfortunately, even though different VLMs in the literature demonstrate impressive visual capabilities in different benchmarks, they are handcrafted by human experts; there is no automated framework to create task-specific multimodal models.
  We introduce Mordal, an automated multimodal model search framework that efficiently finds the best VLM for a user-defined task without manual intervention. Mordal achieves this both by reducing the number of candidates to consider during the search process and by minimizing the time required to evaluate each remaining candidate. Our evaluation shows that Mordal can find the best VLM for a given problem using up to $8.9\times$--$11.6\times$ lower GPU hours than grid search. In the process of our evaluation, we have also discovered new VLMs that outperform their state-of-the-art counterparts.

[Arxiv](https://arxiv.org/abs/2502.00241)