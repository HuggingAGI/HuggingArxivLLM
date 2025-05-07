# 一种基于哈希图的可靠多模型推理共识机制

发布时间：2025年05月06日

`LLM应用

论文摘要讨论了如何处理多个大型语言模型（LLMs）的输出不一致和幻觉问题，提出了一种基于Hashgraph共识算法的机制来聚合这些模型的输出，以提高可靠性和准确性。这属于应用层面的解决方案，因此归类为LLM应用。` `人工智能` `多智能体系统`

> A Hashgraph-Inspired Consensus Mechanism for Reliable Multi-Model Reasoning

# 摘要

> 大型语言模型 (LLMs) 的输出不一致和幻觉现象是构建可靠 AI 系统的重大障碍。当 OpenAI、Google、Anthropic、DeepSeek 和 xAI 等不同厂商的推理模型 (RMs) 面对相同的复杂请求时，由于训练和推理过程的差异，它们往往会产生截然不同的结果。本文提出了一种受分布式账本技术启发的新型共识机制，用于验证和聚合这些输出，将每个 RMs 视为黑盒节点。我们的方法基于 Hashgraph 共识算法，采用ossip-about-gossip 通信和虚拟投票机制，以实现多个 RMs 之间的共识。我们设计了一个原型系统的架构，在该系统中，RMs 会迭代地交换和更新答案，并利用每轮的信息来提高后续轮次的准确性和置信度。与简单的多数投票不同，我们的方法整合了每个模型的知识和交叉验证内容。我们证明了这种受 Hashgraph 启发的共识机制在 AI 集合中的可行性，并概述了其相较于传统集合技术在减少非事实输出方面的优势。本文还讨论了初步的实现考虑、收敛性和准确性的评估标准，以及可能面临的挑战。所提出的机制为多智能体 AI 系统在复杂任务中实现自验证和提供高保真响应展示了一个有前景的方向。

> Inconsistent outputs and hallucinations from large language models (LLMs) are major obstacles to reliable AI systems. When different proprietary reasoning models (RMs), such as those by OpenAI, Google, Anthropic, DeepSeek, and xAI, are given the same complex request, they often produce divergent results due to variations in training and inference. This paper proposes a novel consensus mechanism, inspired by distributed ledger technology, to validate and converge these outputs, treating each RM as a black-box peer. Building on the Hashgraph consensus algorithm, our approach employs gossip-about-gossip communication and virtual voting to achieve agreement among an ensemble of RMs. We present an architectural design for a prototype system in which RMs iteratively exchange and update their answers, using information from each round to improve accuracy and confidence in subsequent rounds. This approach goes beyond simple majority voting by incorporating the knowledge and cross-verification content of every model. We justify the feasibility of this Hashgraph-inspired consensus for AI ensembles and outline its advantages over traditional ensembling techniques in reducing nonfactual outputs. Preliminary considerations for implementation, evaluation criteria for convergence and accuracy, and potential challenges are discussed. The proposed mechanism demonstrates a promising direction for multi-agent AI systems to self-validate and deliver high-fidelity responses in complex tasks.

[Arxiv](https://arxiv.org/abs/2505.03553)