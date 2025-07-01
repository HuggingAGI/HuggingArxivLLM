# 评估多智能体防御机制在大语言模型上的越狱攻击应对效果

发布时间：2025年06月30日

`LLM应用

理由：这篇论文探讨了大型语言模型在面对越狱攻击时的防御机制，特别是通过多智能体系统来增强安全性。它属于LLM的应用层面，因为它专注于实际应用中的安全问题和解决方案。` `模型安全` `多智能体系统`

> Evaluating Multi-Agent Defences Against Jailbreaking Attacks on Large Language Models

# 摘要

> 大型语言模型（LLMs）的最新进展引发了对越狱攻击的担忧，即能够绕过安全机制的提示。本文研究了将多智能体LLM系统作为防御此类攻击的手段。我们评估了三种越狱策略，包括原始的AutoDefense攻击以及来自Deepleaps的BetterDan和JB。通过复现AutoDefense框架，我们将单智能体设置与两智能体和三智能体配置进行了对比。我们的结果显示，多智能体系统增强了抵御越狱攻击的能力，特别是在减少误漏方面。然而，其有效性因攻击类型而异，并带来了权衡，例如增加了误报和计算开销。这些发现揭示了当前自动化防御的局限性，并为未来LLM系统提高对齐鲁棒性提供了方向。


> Recent advances in large language models (LLMs) have raised concerns about jailbreaking attacks, i.e., prompts that bypass safety mechanisms. This paper investigates the use of multi-agent LLM systems as a defence against such attacks. We evaluate three jailbreaking strategies, including the original AutoDefense attack and two from Deepleaps: BetterDan and JB. Reproducing the AutoDefense framework, we compare single-agent setups with two- and three-agent configurations. Our results show that multi-agent systems enhance resistance to jailbreaks, especially by reducing false negatives. However, its effectiveness varies by attack type, and it introduces trade-offs such as increased false positives and computational overhead. These findings point to the limitations of current automated defences and suggest directions for improving alignment robustness in future LLM systems.

[Arxiv](https://arxiv.org/abs/2506.23576)