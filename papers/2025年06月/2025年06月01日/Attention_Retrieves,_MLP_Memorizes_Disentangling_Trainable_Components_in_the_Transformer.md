# 注意力机制负责检索，多层感知机负责记忆：深入解析Transformer中的可训练组件

发布时间：2025年06月01日

`LLM理论` `机器学习` `模型架构`

> Attention Retrieves, MLP Memorizes: Disentangling Trainable Components in the Transformer

# 摘要

> Transformer架构是现代大型语言模型（LLMs）成功的核心，部分原因在于其令人惊讶的能力，即仅通过基于梯度的下一个令牌预测训练，就能执行一系列算法任务，包括数学推理、记忆和检索。虽然Transformer的核心组件是自注意力机制，但我们质疑其性能提升中有多少以及哪些方面可以归因于它。为此，我们将标准Transformer与变体进行比较，这些变体要么将多层感知机（MLP）层冻结在初始化状态，要么将注意力投影器（查询和键）冻结在初始化状态。为了进一步孤立注意力的贡献，我们引入了MixiT——混合Transformer——一种简化的、基于原则的模型，在该模型中注意力系数在初始化时完全随机且固定，消除了任何输入依赖的计算或注意力学习。令人惊讶的是，我们发现MixiT在各种算法任务上的性能与完全训练的Transformer相当，特别是在涉及基本算术或高度依赖记忆的任务中。对于基于检索的任务，我们观察到具有输入依赖的注意力系数始终有益，而MixiT表现不佳。我们将其失败归因于其无法形成专用电路，例如归纳头——一种已知对学习和利用输入序列中重复模式至关重要的特定电路。更有趣的是，我们发现具有冻结键和查询投影器的注意力不仅可以形成归纳头，还可以在语言建模方面表现出竞争力。我们的结果强调了架构异质性的重要性，其中不同的组件提供了互补的归纳偏置，这对于解决不同类别的任务至关重要。

> The Transformer architecture is central to the success of modern Large Language Models (LLMs), in part due to its surprising ability to perform a wide range of algorithmic tasks -- including mathematical reasoning, memorization, and retrieval -- using only gradient-based training on next-token prediction. While the core component of a Transformer is the self-attention mechanism, we question how much, and which aspects, of the performance gains can be attributed to it. To this end, we compare standard Transformers to variants in which either the multi-layer perceptron (MLP) layers or the attention projectors (queries and keys) are frozen at initialization. To further isolate the contribution of attention, we introduce MixiT -- the Mixing Transformer -- a simplified, principled model in which the attention coefficients are entirely random and fixed at initialization, eliminating any input-dependent computation or learning in attention. Surprisingly, we find that MixiT matches the performance of fully trained Transformers on various algorithmic tasks, especially those involving basic arithmetic or focusing heavily on memorization. For retrieval-based tasks, we observe that having input-dependent attention coefficients is consistently beneficial, while MixiT underperforms. We attribute this failure to its inability to form specialized circuits such as induction heads -- a specific circuit known to be crucial for learning and exploiting repeating patterns in input sequences. Even more interestingly, we find that attention with frozen key and query projectors is not only able to form induction heads, but can also perform competitively on language modeling. Our results underscore the importance of architectural heterogeneity, where distinct components contribute complementary inductive biases crucial for solving different classes of tasks.

[Arxiv](https://arxiv.org/abs/2506.01115)