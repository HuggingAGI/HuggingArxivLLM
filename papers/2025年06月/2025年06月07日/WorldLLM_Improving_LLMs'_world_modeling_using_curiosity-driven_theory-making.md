# WorldLLM: 基于好奇心驱动的理论构建方法，提升大型语言模型的世界建模能力

发布时间：2025年06月07日

`Agent` `机器人`

> WorldLLM: Improving LLMs' world modeling using curiosity-driven theory-making

# 摘要

> 大型语言模型（LLMs）虽然具备通用世界知识，但在结构化、领域特定的环境中（如模拟）生成精确预测时往往表现不佳。这是因为它们难以将宽泛、非结构化的理解与特定环境相结合。为此，我们提出了WorldLLM框架，该框架通过结合贝叶斯推断、自主主动探索与强化学习，显著增强了基于LLM的世界建模能力。

WorldLLM巧妙利用了LLM的上下文学习能力，通过自然语言假设引导基于LLM的世界模型进行预测。这些假设在贝叶斯推断框架下不断优化，借助第二个LLM作为提议分布，基于收集到的证据进行调整。而这些证据则是通过一种好奇心驱动的强化学习策略收集的，该策略利用当前假设探索环境，寻找在基于LLM的预测模型下具有低对数似然度的环境转移。

通过交替优化假设和收集新证据，WorldLLM框架实现了预测能力的自主持续提升。实验结果表明，在要求智能体操作和组合物体的文本游戏中，WorldLLM不仅显著提高了预测准确性，还生成了人类可理解的环境动态理论。这一创新性框架为解决LLM在结构化环境中的应用难题提供了全新的思路。

> Large Language Models (LLMs) possess general world knowledge but often struggle to generate precise predictions in structured, domain-specific contexts such as simulations. These limitations arise from their inability to ground their broad, unstructured understanding in specific environments. To address this, we present WorldLLM, a framework that enhances LLM-based world modeling by combining Bayesian inference and autonomous active exploration with reinforcement learning. WorldLLM leverages the in-context learning abilities of LLMs to guide an LLM-based world model's predictions using natural language hypotheses given in its prompt. These hypotheses are iteratively refined through a Bayesian inference framework that leverages a second LLM as the proposal distribution given collected evidence. This evidence is collected using a curiosity-driven reinforcement learning policy that explores the environment to find transitions with a low log-likelihood under our LLM-based predictive model using the current hypotheses. By alternating between refining hypotheses and collecting new evidence, our framework autonomously drives continual improvement of the predictions. Our experiments demonstrate the effectiveness of WorldLLM in a textual game environment that requires agents to manipulate and combine objects. The framework not only enhances predictive accuracy, but also generates human-interpretable theories of environment dynamics.

[Arxiv](https://arxiv.org/abs/2506.06725)