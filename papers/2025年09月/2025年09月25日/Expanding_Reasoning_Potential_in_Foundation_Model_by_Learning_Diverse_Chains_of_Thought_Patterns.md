# 通过学习多样化思维链模式拓展基础模型的推理潜力

发布时间：2025年09月25日

`强化学习` `基础理论`

> Expanding Reasoning Potential in Foundation Model by Learning Diverse Chains of Thought Patterns

# 摘要

> 强化学习（RL）推动了复杂数学推理领域大型推理模型的近期进展。在中期训练阶段融入长思维链（CoT）数据，同样被证实可显著加深模型的推理深度。但现有方法对CoT数据的使用常缺乏针对性，这引出一个核心问题：究竟何种数据类型才能最有效地提升模型的推理能力？

本文首次提出“推理潜力”概念，将基础模型的推理潜力定义为正确回答问题所需独立尝试次数的倒数，该指标与模型最终性能呈强相关性。为此，我们提出利用富含高价值推理模式的多样化数据，以扩展模型的推理潜力。具体做法是：从CoT序列中提炼具有通用性和归纳能力的“原子推理模式”，并基于这些模式构建富含高价值推理模式的核心参考集。进一步，我们提出一种融合推理模式链与token熵的双粒度算法，能从数据池中高效筛选出与核心集匹配的高价值CoT数据（简称CoTP），进而帮助模型高效掌握推理能力。实验表明，仅用10B-token的CoTP数据，85A6B混合专家（MoE）模型在复杂的AIME 2024和2025数据集上性能提升9.58%，下游RL性能上限亦提高7.81%。

> Recent progress in large reasoning models for challenging mathematical reasoning has been driven by reinforcement learning (RL). Incorporating long chain-of-thought (CoT) data during mid-training has also been shown to substantially improve reasoning depth. However, current approaches often utilize CoT data indiscriminately, leaving open the critical question of which data types most effectively enhance model reasoning capabilities. In this paper, we define the foundation model's reasoning potential for the first time as the inverse of the number of independent attempts required to correctly answer the question, which is strongly correlated with the final model performance. We then propose utilizing diverse data enriched with high-value reasoning patterns to expand the reasoning potential. Specifically, we abstract atomic reasoning patterns from CoT sequences, characterized by commonality and inductive capabilities, and use them to construct a core reference set enriched with valuable reasoning patterns. Furthermore, we propose a dual-granularity algorithm involving chains of reasoning patterns and token entropy, efficiently selecting high-value CoT data (CoTP) from the data pool that aligns with the core set, thereby training models to master reasoning effectively. Only 10B-token CoTP data enables the 85A6B Mixture-of-Experts (MoE) model to improve by 9.58% on the challenging AIME 2024 and 2025, and to raise the upper bound of downstream RL performance by 7.81%.

[Arxiv](https://arxiv.org/abs/2509.21124)