# 多LLM系统的自组织主动推理：贝叶斯热力学适应法

发布时间：2024年12月10日

`Agent

理由：这篇论文主要讨论了将主动推理框架与大型语言模型（LLMs）结合，用于创建自适应语言代理。论文的核心在于通过引入主动推理框架来动态调整提示和搜索策略，从而使代理能够更好地适应新信息和变化的环境。这涉及到代理的行为模式、环境建模以及动作选择等，属于Agent（智能代理）的研究范畴。` `人工智能` `语言模型`

> Active Inference for Self-Organizing Multi-LLM Systems: A Bayesian Thermodynamic Approach to Adaptation

# 摘要

> 本文提出了一种将主动推理与大型语言模型（LLMs）结合的新方法，用于创建自适应语言代理。尽管LLMs能力强大，但其依赖静态提示的特性限制了其适应新信息和变化环境的能力。我们通过引入主动推理框架，作为LLM代理的认知层，动态调整提示和搜索策略，解决了这一问题。该框架利用三个状态因素（提示、搜索和信息状态）对环境建模，并通过七个观察模态捕捉质量指标。基于自由能原则，我们系统探索了提示组合和搜索策略。实验结果表明，该方法有效，代理通过观察矩阵中的涌现结构，准确建模了环境动态。动作选择模式展现了从信息收集到针对性提示测试的复杂探索-利用行为。将热力学原理与语言模型结合，为创建稳健、适应性强的代理提供了理论框架，将主动推理从低维控制问题扩展至高维、语言驱动的环境。

> This paper introduces a novel approach to creating adaptive language agents by integrating active inference with large language models (LLMs). While LLMs demonstrate remarkable capabilities, their reliance on static prompts limits adaptation to new information and changing environments. We address this by implementing an active inference framework that acts as a cognitive layer above an LLM-based agent, dynamically adjusting prompts and search strategies through principled information-seeking behavior. Our framework models the environment using three state factors (prompt, search, and information states) with seven observation modalities capturing quality metrics. By framing the agent's learning through the free energy principle, we enable systematic exploration of prompt combinations and search strategies. Experimental results demonstrate the effectiveness of this approach, with the agent developing accurate models of environment dynamics evidenced by emergent structure in observation matrices. Action selection patterns reveal sophisticated exploration-exploitation behavior, transitioning from initial information-gathering to targeted prompt testing. The integration of thermodynamic principles with language model capabilities provides a principled framework for creating robust, adaptable agents, extending active inference beyond traditional low-dimensional control problems to high-dimensional, language-driven environments.

[Arxiv](https://arxiv.org/abs/2412.10425)