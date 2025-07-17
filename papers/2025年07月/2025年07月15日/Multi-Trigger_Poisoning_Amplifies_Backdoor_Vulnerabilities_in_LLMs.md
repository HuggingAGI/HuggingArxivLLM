# 多触发器投毒攻击放大大型语言模型的后门漏洞风险

发布时间：2025年07月15日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在数据中毒攻击中的漏洞，特别是多触发器攻击的机制和防御方法。它深入分析了模型的内在安全问题，并提出了理论上的解决方案，属于LLM理论研究的范畴。` `模型安全` `数据安全`

> Multi-Trigger Poisoning Amplifies Backdoor Vulnerabilities in LLMs

# 摘要

> 研究表明，大型语言模型（LLMs）容易受到数据中毒攻击的影响，攻击者通过在模型中嵌入恶意训练样本，触发特定输入模式下的隐藏行为。然而，现有研究大多仅关注单一触发词的攻击效果，对触发机制和多触发器交互缺乏深入理解。本文提出了一种研究LLMs中毒问题的框架。我们发现，多个独立的后门触发器可以在同一模型中共存而不互相干扰，使攻击者能够同时嵌入多个触发器。通过使用多个具有高嵌入相似性的触发器，我们证明即使在替换部分触发词或被长跨度分隔的情况下，中毒触发器仍能实现稳健激活。我们的研究揭示了LLMs更广泛和持久的漏洞。为应对这一威胁，我们提出了一种基于分层权重差异分析的事后恢复方法，通过选择性重新训练特定模型组件，有效移除触发行为，且参数更新量最小。我们的方法为防御多触发器中毒攻击提供了一种实用高效的解决方案。

> Recent studies have shown that Large Language Models (LLMs) are vulnerable to data poisoning attacks, where malicious training examples embed hidden behaviours triggered by specific input patterns. However, most existing works assume a phrase and focus on the attack's effectiveness, offering limited understanding of trigger mechanisms and how multiple triggers interact within the model. In this paper, we present a framework for studying poisoning in LLMs. We show that multiple distinct backdoor triggers can coexist within a single model without interfering with each other, enabling adversaries to embed several triggers concurrently. Using multiple triggers with high embedding similarity, we demonstrate that poisoned triggers can achieve robust activation even when tokens are substituted or separated by long token spans. Our findings expose a broader and more persistent vulnerability surface in LLMs. To mitigate this threat, we propose a post hoc recovery method that selectively retrains specific model components based on a layer-wise weight difference analysis. Our method effectively removes the trigger behaviour with minimal parameter updates, presenting a practical and efficient defence against multi-trigger poisoning.

[Arxiv](https://arxiv.org/abs/2507.11112)