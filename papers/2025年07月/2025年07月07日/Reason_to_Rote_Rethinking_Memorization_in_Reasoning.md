# 从推理到死记：重新审视推理中的记忆机制

发布时间：2025年07月07日

`LLM理论` `人工智能` `推理系统`

> Reason to Rote: Rethinking Memorization in Reasoning

# 摘要

> 大型语言模型能够轻易记住任意的训练实例，例如标签噪声，然而它们在推理任务上却表现出色。在这项研究中，我们探讨了语言模型如何记忆标签噪声，以及为什么在许多情况下这种记忆并未严重影响可泛化的推理能力。通过使用两个具有噪声标签的可控合成推理数据集——四位数加法（FDA）和两跳关系推理（THR），我们发现记忆过程依赖于可泛化的推理机制：即使检索到噪声标签，模型仍会继续计算中间推理结果，而干预推理过程会对记忆产生不利影响。我们进一步证明，记忆是通过分布式编码实现的，即聚合各种输入和中间结果，而非建立从输入到噪声标签的查找机制。此外，我们的FDA案例研究揭示，记忆是通过异常启发式实现的，其中现有神经元激活模式会轻微调整以适应噪声标签。总的来说，我们的发现表明，语言模型中标签噪声的记忆建立在，而非覆盖，底层推理机制之上，为良性记忆这一引人入胜的现象提供了新的视角。

> Large language models readily memorize arbitrary training instances, such as label noise, yet they perform strikingly well on reasoning tasks. In this work, we investigate how language models memorize label noise, and why such memorization in many cases does not heavily affect generalizable reasoning capabilities. Using two controllable synthetic reasoning datasets with noisy labels, four-digit addition (FDA) and two-hop relational reasoning (THR), we discover a reliance of memorization on generalizable reasoning mechanisms: models continue to compute intermediate reasoning outputs even when retrieving memorized noisy labels, and intervening reasoning adversely affects memorization. We further show that memorization operates through distributed encoding, i.e., aggregating various inputs and intermediate results, rather than building a look-up mechanism from inputs to noisy labels. Moreover, our FDA case study reveals memorization occurs via outlier heuristics, where existing neuron activation patterns are slightly shifted to fit noisy labels. Together, our findings suggest that memorization of label noise in language models builds on, rather than overrides, the underlying reasoning mechanisms, shedding lights on the intriguing phenomenon of benign memorization.

[Arxiv](https://arxiv.org/abs/2507.04782)