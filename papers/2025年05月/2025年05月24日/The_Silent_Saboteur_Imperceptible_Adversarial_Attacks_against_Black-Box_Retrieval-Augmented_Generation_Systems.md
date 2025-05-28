# 无声破坏者：针对黑箱增强生成系统的隐秘对抗攻击

发布时间：2025年05月24日

`RAG`

> The Silent Saboteur: Imperceptible Adversarial Attacks against Black-Box Retrieval-Augmented Generation Systems

# 摘要

> 我们深入研究了针对检索增强生成（RAG）系统的对抗攻击，旨在发现其潜在漏洞。我们专注于生成人类无法察觉的对抗样本，并提出了一种全新的不可察觉检索到生成攻击。这一任务的目标是找到那些能够检索到最初未被包含在初始top-k候选集中的目标文档的不可察觉扰动，从而影响最终答案的生成。为了解决这一问题，我们提出了ReGENT，一个基于强化学习的框架。ReGENT能够跟踪攻击者与目标RAG之间的交互，并根据相关性、生成性和自然性奖励不断优化攻击策略。在新构建的事实性和非事实性问答基准上的实验表明，ReGENT在利用微小的不可察觉文本扰动误导RAG系统方面，显著超越了现有的攻击方法。

> We explore adversarial attacks against retrieval-augmented generation (RAG) systems to identify their vulnerabilities. We focus on generating human-imperceptible adversarial examples and introduce a novel imperceptible retrieve-to-generate attack against RAG. This task aims to find imperceptible perturbations that retrieve a target document, originally excluded from the initial top-$k$ candidate set, in order to influence the final answer generation. To address this task, we propose ReGENT, a reinforcement learning-based framework that tracks interactions between the attacker and the target RAG and continuously refines attack strategies based on relevance-generation-naturalness rewards. Experiments on newly constructed factual and non-factual question-answering benchmarks demonstrate that ReGENT significantly outperforms existing attack methods in misleading RAG systems with small imperceptible text perturbations.

[Arxiv](https://arxiv.org/abs/2505.18583)