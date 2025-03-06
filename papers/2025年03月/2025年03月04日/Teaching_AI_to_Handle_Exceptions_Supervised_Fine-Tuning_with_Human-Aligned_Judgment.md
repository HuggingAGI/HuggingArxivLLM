# 让AI掌握异常处理：人机协同的监督微调

发布时间：2025年03月04日

`LLM应用` `智能体AI系统` `决策智能`

> Teaching AI to Handle Exceptions: Supervised Fine-Tuning with Human-Aligned Judgment

# 摘要

> 大型语言模型（LLMs）最初用于生成式AI，如今正逐渐演变为能在复杂现实情境中做决策的智能体AI系统。尽管其生成能力已被充分验证，但其决策机制仍不为人知，尤其在处理例外情况时——这一环节因合同固有的不完整性而变得至关重要且具挑战性。我们发现，即使是擅长推理的LLMs，也会因严格遵循政策而与人类判断产生显著偏差，即使这种遵循在实际中不可行、次优甚至反效果。我们评估了三种调整AI代理处理例外情况的方法：伦理框架提示、链式推理和监督微调。结果显示，伦理框架提示失败，链式推理仅小幅改进，而结合人类解释的监督微调效果显著。令人惊讶的是，监督微调甚至使模型能够将类人决策推广到新场景，展示了跨情境下与人类决策对齐的迁移学习能力。此外，仅用解释而非标签进行微调至关重要，表明要使LLMs与人类判断对齐，需在如何决策方面进行明确训练。这些发现强调了解决LLMs在处理例外情况方面不足的重要性，以引导能动型AI的发展，使其有效与人类判断对齐并适应新情境。

> Large language models (LLMs), initially developed for generative AI, are now evolving into agentic AI systems, which make decisions in complex, real-world contexts. Unfortunately, while their generative capabilities are well-documented, their decision-making processes remain poorly understood. This is particularly evident when models are handling exceptions, a critical and challenging aspect of decision-making made relevant by the inherent incompleteness of contracts. Here we demonstrate that LLMs, even ones that excel at reasoning, deviate significantly from human judgments because they adhere strictly to policies, even when such adherence is impractical, suboptimal, or even counterproductive. We then evaluate three approaches to tuning AI agents to handle exceptions: ethical framework prompting, chain-of-thought reasoning, and supervised fine-tuning. We find that while ethical framework prompting fails and chain-of-thought prompting provides only slight improvements, supervised fine-tuning, specifically with human explanations, yields markedly better results. Surprisingly, in our experiments, supervised fine-tuning even enabled models to generalize human-like decision-making to novel scenarios, demonstrating transfer learning of human-aligned decision-making across contexts. Furthermore, fine-tuning with explanations, not just labels, was critical for alignment, suggesting that aligning LLMs with human judgment requires explicit training on how decisions are made, not just which decisions are made. These findings highlight the need to address LLMs' shortcomings in handling exceptions in order to guide the development of agentic AI toward models that can effectively align with human judgment and simultaneously adapt to novel contexts.

[Arxiv](https://arxiv.org/abs/2503.02976)