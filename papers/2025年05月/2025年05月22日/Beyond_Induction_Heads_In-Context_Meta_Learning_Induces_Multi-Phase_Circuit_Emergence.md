# 超越归纳头：上下文元学习触发多阶段电路的涌现

发布时间：2025年05月22日

`LLM理论` `元学习机制`

> Beyond Induction Heads: In-Context Meta Learning Induces Multi-Phase Circuit Emergence

# 摘要

> 基于Transformer的语言模型具备In-Context Learning（ICL）能力，能根据上下文自适应地进行预测。虽然先前研究通过准确率突变将归纳头与ICL联系起来，但这种关联仅适用于答案包含在上下文中的情况。实际上，大型语言模型中实用的ICL关键在于从上下文中元学习解决问题的方法，而非简单复制答案；然而，这种能力是如何在训练中形成的，目前尚不明确。本文通过分析模型电路在训练过程中的动态变化，揭示了元学习能力的获取机制。具体来说，我们将先前的复制任务扩展到In-Context Meta Learning框架中，要求模型通过示例推断任务以回答查询。有趣的是，在这一框架下，我们发现获取这种能力的过程分为多个阶段，每个阶段都会形成独特的电路，与归纳头的单一阶段变化形成鲜明对比。这种电路的出现与大型语言模型中已知的多种现象相关，我们的研究为理解Transformer的ICL能力来源提供了更深入的洞察。

> Transformer-based language models exhibit In-Context Learning (ICL), where predictions are made adaptively based on context. While prior work links induction heads to ICL through a sudden jump in accuracy, this can only account for ICL when the answer is included within the context. However, an important property of practical ICL in large language models is the ability to meta-learn how to solve tasks from context, rather than just copying answers from context; how such an ability is obtained during training is largely unexplored. In this paper, we experimentally clarify how such meta-learning ability is acquired by analyzing the dynamics of the model's circuit during training. Specifically, we extend the copy task from previous research into an In-Context Meta Learning setting, where models must infer a task from examples to answer queries. Interestingly, in this setting, we find that there are multiple phases in the process of acquiring such abilities, and that a unique circuit emerges in each phase, contrasting with the single-phases change in induction heads. The emergence of such circuits can be related to several phenomena known in large language models, and our analysis lead to a deeper understanding of the source of the transformer's ICL ability.

[Arxiv](https://arxiv.org/abs/2505.16694)