# # 绿心：专为结构化与逻辑推理打造的越南语新一代大型语言模型

发布时间：2025年04月23日

`LLM应用` `多语言技术`

> GreenMind: A Next-Generation Vietnamese Large Language Model for Structured and Logical Reasoning

# 摘要

> Chain-of-Thought (CoT) 是一种强大的方法，用于处理需要中间推理步骤的 LLM 任务。本文介绍了一种名为 GreenMind-Medium-14B-R1 的越南语推理模型，该模型基于 Group Relative Policy Optimization 的微调策略。我们还利用了一个高质量的越南语合成推理数据集，并设计了两个奖励函数来解决该技术的两大限制：(i) 在采样过程中显式检测偏见语言字符以应对语言混合问题；(ii) 借助 Sentence Transformer 模型，确保推理内容的事实准确性，避免扭曲最终输出。实验结果表明，我们的模型在 VLSP 2023 挑战赛的越南语数据集上表现优于先前方法，显著提升了响应的 linguistic consistency。此外，我们在多语言多项选择数据集 SeaExam 上的评估进一步证明了我们推理方法相较于 few-shot prompting 技术的优越性。

> Chain-of-Thought (CoT) is a robust approach for tackling LLM tasks that require intermediate reasoning steps prior to generating a final answer. In this paper, we present GreenMind-Medium-14B-R1, the Vietnamese reasoning model inspired by the finetuning strategy based on Group Relative Policy Optimization. We also leverage a high-quality Vietnamese synthesized reasoning dataset and design two reward functions to tackle the main limitations of this technique: (i) language mixing, where we explicitly detect the presence of biased language characters during the process of sampling tokens, and (ii) we leverage Sentence Transformer-based models to ensure that the generated reasoning content maintains factual correctness and does not distort the final output. Experimental results on the Vietnamese dataset from the VLSP 2023 Challenge demonstrate that our model outperforms prior works and enhances linguistic consistency in its responses. Furthermore, we extend our evaluation to SeaExam-a multilingual multiple-choice dataset, showing the effectiveness of our reasoning method compared to few-shot prompting techniques.

[Arxiv](https://arxiv.org/abs/2504.16832)