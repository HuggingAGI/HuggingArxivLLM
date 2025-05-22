# # 概念不一致：时间与死亡在角色扮演中的探索

发布时间：2025年05月20日

`LLM理论` `人工智能`

> Concept Incongruence: An Exploration of Time and Death in Role Playing

# 摘要

> 想象一下，当提示是“画一只长着两个角的独角兽”时，大型语言模型（LLMs）是否应该识别出独角兽在定义上只有一个角，并请求用户澄清，还是继续生成内容？我们提出了“概念不一致”这一概念，用于描述当用户提示或模型表示中的概念边界发生冲突时，导致行为 underspecified 或 mis-specified 的现象。在本研究中，我们首次尝试定义和分析概念不一致下的模型行为。聚焦于角色扮演设置中的时间边界问题，我们提出了三个行为指标——弃权率、条件准确性和回答率——来量化由于角色死亡导致的概念不一致下的模型行为。实验结果表明，模型在角色死亡后无法有效弃权，且与非角色扮演设置相比，准确率显著下降。通过深入探查，我们发现主要原因在于：(i) 不同年份中对“死亡”状态的编码不够稳定，导致弃权行为表现不佳；(ii) 角色扮演改变了模型的时间表示，从而影响了整体准确率。基于这些发现，我们提出改进模型弃权和回答行为一致性的方法。我们的研究揭示了概念不一致如何引发意外的模型行为，并为未来改进这一领域提供了重要方向。

> Consider this prompt "Draw a unicorn with two horns". Should large language models (LLMs) recognize that a unicorn has only one horn by definition and ask users for clarifications, or proceed to generate something anyway? We introduce concept incongruence to capture such phenomena where concept boundaries clash with each other, either in user prompts or in model representations, often leading to under-specified or mis-specified behaviors. In this work, we take the first step towards defining and analyzing model behavior under concept incongruence. Focusing on temporal boundaries in the Role-Play setting, we propose three behavioral metrics--abstention rate, conditional accuracy, and answer rate--to quantify model behavior under incongruence due to the role's death. We show that models fail to abstain after death and suffer from an accuracy drop compared to the Non-Role-Play setting. Through probing experiments, we identify two main causes: (i) unreliable encoding of the "death" state across different years, leading to unsatisfactory abstention behavior, and (ii) role playing causes shifts in the model's temporal representations, resulting in accuracy drops. We leverage these insights to improve consistency in the model's abstention and answer behaviors. Our findings suggest that concept incongruence leads to unexpected model behaviors and point to future directions on improving model behavior under concept incongruence.

[Arxiv](https://arxiv.org/abs/2505.14905)