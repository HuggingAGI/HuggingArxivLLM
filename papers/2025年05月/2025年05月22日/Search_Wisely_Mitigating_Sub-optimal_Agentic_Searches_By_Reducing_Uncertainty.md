# # 摘要
# 聪明搜索：通过降低不确定性缓解次优的代理搜索

发布时间：2025年05月22日

`Agent` `问答系统`

> Search Wisely: Mitigating Sub-optimal Agentic Searches By Reducing Uncertainty

# 摘要

> 智能体增强检索生成（RAG）系统通过支持动态的多步骤推理和信息检索，显著增强了大型语言模型的能力。然而，这些系统常常表现出低效的搜索行为，如过度搜索（检索冗余信息）和搜索不足（未能检索必要信息），这严重影响了系统的效率和可靠性。本研究正式定义并量化了这些行为，发现它们在多个问答数据集和智能体 RAG 系统中普遍存在（例如，某个模型可以在 27.7% 的搜索步骤中避免不必要的搜索）。此外，我们发现这些低效行为与模型对自己知识边界的不确定性之间存在重要关联，其中回答的准确性与模型在搜索决策中的不确定性密切相关。为了解决这一问题，我们提出了一种基于强化学习的训练方法 β-GRPO，该方法通过引入置信度阈值，奖励高确定性的搜索决策。在七个问答基准测试中的实验表明，β-GRPO 方法使 30 亿参数的模型具备了更强大的 RAG 能力，平均精确匹配得分比其他强基线高出 4%。

> Agentic Retrieval-Augmented Generation (RAG) systems enhance Large Language Models (LLMs) by enabling dynamic, multi-step reasoning and information retrieval. However, these systems often exhibit sub-optimal search behaviors like over-search (retrieving redundant information) and under-search (failing to retrieve necessary information), which hinder efficiency and reliability. This work formally defines and quantifies these behaviors, revealing their prevalence across multiple QA datasets and agentic RAG systems (e.g., one model could have avoided searching in 27.7% of its search steps). Furthermore, we demonstrate a crucial link between these inefficiencies and the models' uncertainty regarding their own knowledge boundaries, where response accuracy correlates with model's uncertainty in its search decisions. To address this, we propose $β$-GRPO, a reinforcement learning-based training method that incorporates confidence threshold to reward high-certainty search decisions. Experiments on seven QA benchmarks show that $β$-GRPO enable a 3B model with better agentic RAG ability, outperforming other strong baselines with a 4% higher average exact match score.

[Arxiv](https://arxiv.org/abs/2505.17281)