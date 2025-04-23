# Think2SQL：提升 LLM 推理能力，助力 Text2SQL 任务

发布时间：2025年04月21日

`LLM应用` `数据库` `人工智能`

> Think2SQL: Reinforce LLM Reasoning Capabilities for Text2SQL

# 摘要

> 大型语言模型 (LLMs) 在将自然语言问题转化为 SQL 查询方面表现优异。然而，小规模 LLMs 在零样本学习 (ZSL) 设置下，处理多表和复杂 SQL 模式的查询仍具挑战性。监督微调 (SFT) 能部分弥补预训练模型的不足，但面对多跳推理任务仍显力不从心。为解决这一问题，研究者提出了多种强化推理能力的 LLM 训练策略，包括在 ZSL 中引入思维过程、在 SFT 中加入推理轨迹，或采用强化学习 (RL) 策略。然而，推理对 Text2SQL 性能的具体影响尚未得到充分研究。本研究旨在探究 LLM 的推理能力在四个基准数据集上对 Text2SQL 任务的影响力。为此，我们考察了以下四种 LLM 设置：(1) ZSL，是否包含通用推理；(2) SFT，是否包含任务特定的推理轨迹；(3) RL，以执行准确性为主要奖励函数；(4) SFT+RL，即结合 SFT 和 RL 的两阶段方法。研究结果表明，在 ZSL 设置下，通用推理对复杂 Text2SQL 案例的处理效果有限。小规模 LLMs 从带推理的 SFT 中获益匪浅，显著弥补了其较弱的预训练基础。强化学习 (RL) 在所有测试模型和数据集上均表现出色，尤其在处理多跳推理和多表 SQL 查询时优势明显。得益于在推理过程的通用性和执行准确性的优化之间找到了平衡，结合了 SFT+RL 的小规模 LLMs 在大多数复杂数据集上表现尤为突出。值得注意的是，得益于 RL 的优化，7B 参数的 Qwen-Coder-2.5 模型在 Bird 数据集上的表现已可与拥有 1000 多亿参数的模型相媲美。

> Large Language Models (LLMs) have shown impressive capabilities in transforming natural language questions about relational databases into SQL queries. Despite recent improvements, small LLMs struggle to handle questions involving multiple tables and complex SQL patterns under a Zero-Shot Learning (ZSL) setting. Supervised Fine-Tuning (SFT) partially compensate the knowledge deficits in pretrained models but falls short while dealing with queries involving multi-hop reasoning. To bridge this gap, different LLM training strategies to reinforce reasoning capabilities have been proposed, ranging from leveraging a thinking process within ZSL, including reasoning traces in SFT, or adopt Reinforcement Learning (RL) strategies. However, the influence of reasoning on Text2SQL performance is still largely unexplored. This paper investigates to what extent LLM reasoning capabilities influence their Text2SQL performance on four benchmark datasets. To this end, it considers the following LLM settings: (1) ZSL, including general-purpose reasoning or not; (2) SFT, with and without task-specific reasoning traces; (3) RL, leveraging execution accuracy as primary reward function; (4) SFT+RL, i.e, a two-stage approach that combines SFT and RL. The results show that general-purpose reasoning under ZSL proves to be ineffective in tackling complex Text2SQL cases. Small LLMs benefit from SFT with reasoning much more than larger ones, bridging the gap of their (weaker) model pretraining. RL is generally beneficial across all tested models and datasets, particularly when SQL queries involve multi-hop reasoning and multiple tables. Small LLMs with SFT+RL excel on most complex datasets thanks to a strategic balance between generality of the reasoning process and optimization of the execution accuracy. Thanks to RL, the7B Qwen-Coder-2.5 model performs on par with 100+ Billion ones on the Bird dataset.

[Arxiv](https://arxiv.org/abs/2504.15077)