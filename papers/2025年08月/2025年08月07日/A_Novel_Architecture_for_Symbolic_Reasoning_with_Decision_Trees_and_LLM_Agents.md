# 基于决策树与LLM代理的符号推理创新架构

发布时间：2025年08月07日

`Agent` `临床决策支持` `科学发现`

> A Novel Architecture for Symbolic Reasoning with Decision Trees and LLM Agents

# 摘要

> 我们提出了一种混合架构，它在一个协调的多智能体框架内整合了基于决策树的符号推理与大型语言模型（LLMs）的生成能力。与之前松散耦合符号和神经模块的方法不同，我们的设计将决策树和随机森林嵌入到一个统一的推理系统中，作为可调用的预言。基于树的模块实现了可解释的规则推理和因果逻辑，而LLM智能体负责 abduction推理、泛化和交互式规划。一个中央编排器维护信念状态的一致性，并在智能体和外部工具之间调解通信，从而支持对结构化和非结构化输入的推理。该系统在推理基准上表现出色。在	extit{ProofWriter}上，通过逻辑基础的树验证，它将蕴含一致性提高了+7.2%。在GSM8k上，通过符号增强，它在多步数学问题上实现了+5.3%的准确率提升。在	extit{ARC}上，通过符号预言的整合，它将抽象准确性提高了+6.0%。在临床决策支持和科学发现中的应用展示了该系统如何通过符号编码领域规则，同时利用LLMs进行上下文推理和假设生成。这种架构为通用神经符号推理提供了一个强大、可解释且可扩展的解决方案。

> We propose a hybrid architecture that integrates decision tree-based symbolic reasoning with the generative capabilities of large language models (LLMs) within a coordinated multi-agent framework. Unlike prior approaches that loosely couple symbolic and neural modules, our design embeds decision trees and random forests as callable oracles within a unified reasoning system. Tree-based modules enable interpretable rule inference and causal logic, while LLM agents handle abductive reasoning, generalization, and interactive planning. A central orchestrator maintains belief state consistency and mediates communication across agents and external tools, enabling reasoning over both structured and unstructured inputs.
  The system achieves strong performance on reasoning benchmarks. On \textit{ProofWriter}, it improves entailment consistency by +7.2\% through logic-grounded tree validation. On GSM8k, it achieves +5.3\% accuracy gains in multistep mathematical problems via symbolic augmentation. On \textit{ARC}, it boosts abstraction accuracy by +6.0\% through integration of symbolic oracles. Applications in clinical decision support and scientific discovery show how the system encodes domain rules symbolically while leveraging LLMs for contextual inference and hypothesis generation. This architecture offers a robust, interpretable, and extensible solution for general-purpose neuro-symbolic reasoning.

[Arxiv](https://arxiv.org/abs/2508.05311)