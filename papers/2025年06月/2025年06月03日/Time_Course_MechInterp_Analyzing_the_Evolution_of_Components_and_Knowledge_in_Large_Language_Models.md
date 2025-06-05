# 时间进程 MechInterp：解析大型语言模型中组件与知识的演变过程

发布时间：2025年06月03日

`LLM理论` `机器学习`

> Time Course MechInterp: Analyzing the Evolution of Components and Knowledge in Large Language Models

# 摘要

> 理解大型语言模型 (LLMs) 如何获取和存储事实知识对于提升其可解释性和可靠性至关重要。在本研究中，我们通过追踪 OLMo-7B 模型在预训练过程中注意力头和前馈网络 (FFNs) 的角色演变，揭示了事实知识表示的进化过程。我们将这些组件分为通用型、实体型、关系-答案型和事实-答案型四类，并深入研究了它们的稳定性与转变规律。研究发现，LLMs 初期依赖广泛适用的通用组件，随着训练的推进，这些组件逐渐专业化。一旦模型能够可靠预测答案，部分组件会被重新分配用途，这表明了一种适应性学习机制。值得注意的是，注意力头显示出最高的周转率，而前馈网络则在整个训练过程中保持了更高的稳定性。进一步的探测实验表明，基于位置的关系在训练早期比基于名称的关系更快地达到高精度，凸显了任务复杂性如何塑造知识获取的动态过程。这些发现为理解 LLMs 中的知识形成机制提供了重要见解。


> Understanding how large language models (LLMs) acquire and store factual knowledge is crucial for enhancing their interpretability and reliability. In this work, we analyze the evolution of factual knowledge representation in the OLMo-7B model by tracking the roles of its attention heads and feed forward networks (FFNs) over the course of pre-training. We classify these components into four roles: general, entity, relation-answer, and fact-answer specific, and examine their stability and transitions. Our results show that LLMs initially depend on broad, general-purpose components, which later specialize as training progresses. Once the model reliably predicts answers, some components are repurposed, suggesting an adaptive learning process. Notably, attention heads display the highest turnover. We also present evidence that FFNs remain more stable throughout training. Furthermore, our probing experiments reveal that location-based relations converge to high accuracy earlier in training than name-based relations, highlighting how task complexity shapes acquisition dynamics. These insights offer a mechanistic view of knowledge formation in LLMs.

[Arxiv](https://arxiv.org/abs/2506.03434)