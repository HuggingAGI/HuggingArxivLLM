# 小向量，大影响：基于引导向量的强化学习诱导推理机制研究

发布时间：2025年09月08日

`LLM理论` `基础理论`

> Small Vectors, Big Effects: A Mechanistic Study of RL-Induced Reasoning via Steering Vectors

# 摘要

> 推理训练如何重塑语言模型计算的机制目前仍不明确。我们研究了插入基础模型残差流的轻量级引导向量，这些向量经强化学习目标训练后，既能达到全微调的性能水平，又保留了小型附加干预的可解释性。通过logit-lens读取、路径修补与电路分析，我们对两个模型展开研究，发现：（i）最后一层引导向量的作用类似于集中在首个生成token上的token替换偏差，会持续提升“To”“Step”等token；（ii）倒数第二层引导向量基本不改变注意力模式，而是通过MLP和未嵌入层发挥作用，优先对过程词和结构符号进行加权。这些结果为解释推理训练引发的行为变化构建了一套原则性框架。

> The mechanisms by which reasoning training reshapes language-model computations remain poorly understood. We study lightweight steering vectors inserted into the base model's residual stream and trained with a reinforcement-learning objective, which can match full fine-tuning performance while retaining the interpretability of small, additive interventions. Using logit-lens readouts, path patching, and circuit analyses, we analyze two models and find: (i) the last-layer steering vector behaves like a token-substitution bias concentrated on the first generated token, consistently boosting tokens such as "To" and "Step"; and (ii) the penultimate-layer steering vector leaves attention patterns largely unchanged and instead acts through the MLP and unembedding, preferentially up-weighting process words and structure symbols. These results establish a principled framework for interpreting the behavioral changes induced by reasoning training.

[Arxiv](https://arxiv.org/abs/2509.06608)