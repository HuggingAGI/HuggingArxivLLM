# 因果头部门控：理解Transformer中注意力头角色的框架

发布时间：2025年05月19日

`LLM理论` `人工智能`

> Causal Head Gating: A Framework for Interpreting Roles of Attention Heads in Transformers

# 摘要

> 我们提出因果头门控（CHG），这是一种用于解释Transformer模型中注意力头功能角色的可扩展方法。CHG通过学习软门控，并根据注意力头对任务性能的影响，将它们分类为促进、干扰或无关。与传统的基于假设的机制可解释性方法不同，CHG无需依赖提示模板或目标标签，而是直接通过标准的下一个令牌预测应用于任何数据集。我们在Llama 3模型家族中的多个大型语言模型（LLMs）以及多样化的任务上评估了CHG，包括句法、常识和数学推理，并展示了CHG得分提供了因果——而不仅仅是相关性——见解，这些见解通过消融和因果中介分析得到了验证。我们还引入了对比CHG，这是一种变体，能够分离特定任务组件的子电路。我们的研究发现表明，LLMs包含多个稀疏且足够的子电路，单个注意力头的角色取决于与其他头的交互（低模块化），而指令遵循和上下文学习依赖于可分离的机制。

> We present causal head gating (CHG), a scalable method for interpreting the functional roles of attention heads in transformer models. CHG learns soft gates over heads and assigns them a causal taxonomy - facilitating, interfering, or irrelevant - based on their impact on task performance. Unlike prior approaches in mechanistic interpretability, which are hypothesis-driven and require prompt templates or target labels, CHG applies directly to any dataset using standard next-token prediction. We evaluate CHG across multiple large language models (LLMs) in the Llama 3 model family and diverse tasks, including syntax, commonsense, and mathematical reasoning, and show that CHG scores yield causal - not merely correlational - insight, validated via ablation and causal mediation analyses. We also introduce contrastive CHG, a variant that isolates sub-circuits for specific task components. Our findings reveal that LLMs contain multiple sparse, sufficient sub-circuits, that individual head roles depend on interactions with others (low modularity), and that instruction following and in-context learning rely on separable mechanisms.

[Arxiv](https://arxiv.org/abs/2505.13737)