# 推理分歧：模型的思维过程如何主导多智能体系统中的说服

发布时间：2025年09月25日

`Agent` `基础理论`

> Disagreements in Reasoning: How a Model's Thinking Process Dictates Persuasion in Multi-Agent Systems

# 摘要

> 近年来，多智能体系统（MAS）迅速发展，其中大型语言模型（LLMs）与大型推理模型（LRMs）常通过协作解决复杂问题，这使得深入理解智能体间交互的说服动态变得尤为必要。本文对“说服效果主要取决于模型规模”这一主流假设提出了挑战。相反，我们认为这些动态本质上由模型的底层认知过程决定，尤其是其显式推理能力。通过一系列多智能体说服实验，我们发现了一种核心权衡关系，并将其命名为“说服二元性”。研究结果显示，LRMs的推理过程具有显著更强的抗说服性，能更稳固地坚持其初始信念；反之，若通过分享“思考内容”让推理过程透明化，则会大幅提升它们的说服能力。我们进一步探究了更复杂的传递式说服场景，揭示了多智能体网络中多跳说服过程中影响传播与衰减的复杂动态。本研究系统地证明了模型内部处理架构与其外部说服行为的关联，为先进模型的易受影响性提供了全新解释，同时也为未来MAS的安全性、鲁棒性及设计方向带来了关键启示。

> The rapid proliferation of recent Multi-Agent Systems (MAS), where Large Language Models (LLMs) and Large Reasoning Models (LRMs) usually collaborate to solve complex problems, necessitates a deep understanding of the persuasion dynamics that govern their interactions. This paper challenges the prevailing hypothesis that persuasive efficacy is primarily a function of model scale. We propose instead that these dynamics are fundamentally dictated by a model's underlying cognitive process, especially its capacity for explicit reasoning. Through a series of multi-agent persuasion experiments, we uncover a fundamental trade-off we term the Persuasion Duality. Our findings reveal that the reasoning process in LRMs exhibits significantly greater resistance to persuasion, maintaining their initial beliefs more robustly. Conversely, making this reasoning process transparent by sharing the "thinking content" dramatically increases their ability to persuade others. We further consider more complex transmission persuasion situations and reveal complex dynamics of influence propagation and decay within multi-hop persuasion between multiple agent networks. This research provides systematic evidence linking a model's internal processing architecture to its external persuasive behavior, offering a novel explanation for the susceptibility of advanced models and highlighting critical implications for the safety, robustness, and design of future MAS.

[Arxiv](https://arxiv.org/abs/2509.21054)