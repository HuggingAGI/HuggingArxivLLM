# GUARD:针对神经代码生成中的链式思维的双智能体后门防御方法

发布时间：2025年05月27日

`LLM应用` `代码生成` `网络安全`

> GUARD:Dual-Agent based Backdoor Defense on Chain-of-Thought in Neural Code Generation

# 摘要

> 大型语言模型在代码生成领域的广泛应用带来了新的研究突破。研究表明，引入链式推理生成模型能够显著提升代码生成效果，通过提供明确的推理步骤实现这一目标。然而，作为外部组件，链式推理模型特别容易受到后门攻击，现有防御机制往往难以有效检测此类攻击。为应对这一挑战，我们提出GUARD，一个专为神经代码生成中链式推理后门攻击设计的创新双代理防御框架。GUARD整合了两大核心组件：GUARD-Judge，通过全面分析识别可疑的链式推理步骤和潜在触发器；以及GUARD-Repair，采用检索增强生成方法，针对已识别的异常重新生成安全的链式推理步骤。实验结果表明，GUARD不仅有效抵御攻击，还能保持生成质量，推动了安全代码生成系统的发展。

> With the widespread application of large language models in code generation, recent studies demonstrate that employing additional Chain-of-Thought generation models can significantly enhance code generation performance by providing explicit reasoning steps. However, as external components, CoT models are particularly vulnerable to backdoor attacks, which existing defense mechanisms often fail to detect effectively. To address this challenge, we propose GUARD, a novel dual-agent defense framework specifically designed to counter CoT backdoor attacks in neural code generation. GUARD integrates two core components: GUARD-Judge, which identifies suspicious CoT steps and potential triggers through comprehensive analysis, and GUARD-Repair, which employs a retrieval-augmented generation approach to regenerate secure CoT steps for identified anomalies. Experimental results show that GUARD effectively mitigates attacks while maintaining generation quality, advancing secure code generation systems.

[Arxiv](https://arxiv.org/abs/2505.21425)