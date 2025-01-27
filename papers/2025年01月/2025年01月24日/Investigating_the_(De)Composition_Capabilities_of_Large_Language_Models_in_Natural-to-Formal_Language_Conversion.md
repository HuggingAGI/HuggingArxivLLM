# # 探究大型语言模型在自然语言到形式语言转换中的（解）组合能力

发布时间：2025年01月24日

`LLM理论

**理由**：这篇论文主要探讨了大型语言模型（LLMs）在自然语言到形式语言转换（N2F）中的分解与组合能力，并提出了一个评估框架（DEDC）来解耦和评估这些能力。研究重点在于分析LLMs在这些任务中的表现和不足，属于对LLMs内在能力和理论基础的探讨，因此归类为LLM理论。` `形式语言`

> Investigating the (De)Composition Capabilities of Large Language Models in Natural-to-Formal Language Conversion

# 摘要

> 为了实现通用且鲁棒的自然语言到形式语言转换（N2F），大型语言模型（LLMs）在面对陌生形式语言时，必须具备强大的分解与组合能力，并能应对组合性差距和反直觉符号名称的挑战。为探究LLMs是否具备这些基本能力，我们提出了DEDC框架。该框架通过半自动化的样本与任务构建，实现了对LLMs在N2F中分解与组合能力的解耦评估。基于此框架，我们对最先进的LLMs进行了评估与分析，主要发现如下：（1）LLMs在分解与组合方面均存在不足；（2）LLMs的错误类型广泛，主要源于自然语言理解的缺陷及符号系统的学习与使用问题；（3）组合性差距与反直觉符号名称均会影响LLMs的分解与组合表现。本研究为探索LLMs在N2F中的基本能力提供了新视角，对不足与归因的深入分析将助力LLMs的后续优化。

> To achieve generalized and robust natural-to-formal language conversion (N2F), large language models (LLMs) need to have strong capabilities of decomposition and composition in N2F when faced with an unfamiliar formal language and be able to cope with compositional gaps and counter-intuitive symbolic names. To investigate whether LLMs have this set of basic capabilities in N2F, we propose the DEDC framework. This framework semi-automatically performs sample and task construction, allowing decoupled evaluation of the set of decomposition and composition capabilities of LLMs in N2F. Based on this framework, we evaluate and analyze the most advanced LLMs, and the main findings include that: (1) the LLMs are deficient in both decomposition and composition; (2) the LLMs show a wide coverage of error types that can be attributed to deficiencies in natural language understanding and the learning and use of symbolic systems; (3) compositional gaps and counter-intuitive symbolic names both affect the decomposition and composition of the LLMs. Our work provides a new perspective for investigating the basic capabilities of decomposition and composition of LLMs in N2F. The detailed analysis of deficiencies and attributions can help subsequent improvements of LLMs.

[Arxiv](https://arxiv.org/abs/2501.14649)