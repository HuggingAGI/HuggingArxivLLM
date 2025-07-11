# 上下文学习中重复神经元与归纳头部的理解与控制

发布时间：2025年07月10日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）内部机制，特别是重复神经元对上下文学习（ICL）性能的影响，属于对模型理论的深入研究。` `人工智能`

> Understanding and Controlling Repetition Neurons and Induction Heads in In-Context Learning

# 摘要

> 本文探讨了大型语言模型（LLMs）识别重复输入模式的能力与其上下文学习（ICL）表现之间的关系。与以往专注于注意力头的研究不同，我们从技能神经元，特别是重复神经元的视角进行分析。实验结果表明，重复神经元对ICL性能的影响取决于其所在层的深度。通过对比重复神经元与归纳头的效果，我们找到了在减少重复输出的同时保持强大ICL能力的策略。

> This paper investigates the relationship between large language models' (LLMs) ability to recognize repetitive input patterns and their performance on in-context learning (ICL). In contrast to prior work that has primarily focused on attention heads, we examine this relationship from the perspective of skill neurons, specifically repetition neurons. Our experiments reveal that the impact of these neurons on ICL performance varies depending on the depth of the layer in which they reside. By comparing the effects of repetition neurons and induction heads, we further identify strategies for reducing repetitive outputs while maintaining strong ICL capabilities.

[Arxiv](https://arxiv.org/abs/2507.07810)