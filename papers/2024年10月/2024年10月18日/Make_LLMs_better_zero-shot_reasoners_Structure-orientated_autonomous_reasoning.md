# 提升LLMs的零-shot推理能力：结构导向的自主推理

发布时间：2024年10月18日

`Agent

理由：这篇论文提出了一种名为“结构导向自主推理代理（SARA）”的系统，该系统通过细化技术和外部知识检索能力来提升复杂问答任务的可靠性。这表明该论文主要关注的是构建一个能够自主推理的代理系统，因此应归类为Agent。` `问答系统`

> Make LLMs better zero-shot reasoners: Structure-orientated autonomous reasoning

# 摘要

> # 摘要
大型语言模型（LLMs）的零-shot推理方法具有显著优势，如强大的泛化能力和减少对人类示例的依赖。然而，当前方法在复杂任务（如多步推理问题）中仍有不足。本文提出了一种新颖的结构导向分析方法，帮助LLMs更好地理解问题并优化推理过程。我们展示了现有策略（如思维链和反应）如何从中受益，并通过概率图模型从理论上解释了其有效性。为进一步提升复杂问答任务的可靠性，我们提出了结构导向自主推理代理（SARA），该系统通过细化技术和外部知识检索能力，显著减少了事实错误。大量实验验证了其有效性，甚至在某些情况下超越了少样本方法。此外，该系统在复杂任务中表现出更高的推理准确性和对攻击的鲁棒性。

> Zero-shot reasoning methods with Large Language Models (LLMs) offer significant advantages including great generalization to novel tasks and reduced dependency on human-crafted examples. However, the current zero-shot methods still have limitations in complex tasks, e.g., answering questions that require multi-step reasoning. In this paper, we address this limitation by introducing a novel structure-oriented analysis method to help LLMs better understand the question and guide the problem-solving process of LLMs. We first demonstrate how the existing reasoning strategies, Chain-of-Thought and ReAct, can benefit from our structure-oriented analysis. In addition to empirical investigations, we leverage the probabilistic graphical model to theoretically explain why our structure-oriented analysis can improve the LLM reasoning process. To further improve the reliability in complex question-answering tasks, we propose a multi-agent reasoning system, Structure-oriented Autonomous Reasoning Agents (SARA), that can better enforce the reasoning process following our structure-oriented analysis by refinement techniques and is equipped with external knowledge retrieval capability to reduce factual errors. Extensive experiments verify the effectiveness of the proposed reasoning system. Surprisingly, in some cases, the system even surpasses few-shot methods. Finally, the system not only improves reasoning accuracy in complex tasks but also demonstrates robustness against potential attacks that corrupt the reasoning process.

[Arxiv](https://arxiv.org/abs/2410.19000)