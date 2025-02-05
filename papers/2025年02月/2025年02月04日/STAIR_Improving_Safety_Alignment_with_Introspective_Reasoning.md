# STAIR: 利用内省推理优化安全对齐

发布时间：2025年02月04日

`LLM理论

理由：这篇论文主要讨论了如何通过STAIR框架来改进大型语言模型（LLMs）的安全性和无害性，特别是通过自我改进的链式思维（CoT）推理和安全信息蒙特卡洛树搜索（SI-MCTS）来增强模型的安全对齐。这些内容涉及到LLM的理论改进和安全性研究，因此应归类为LLM理论。` `人工智能`

> STAIR: Improving Safety Alignment with Introspective Reasoning

# 摘要

> 确保大型语言模型（LLMs）的安全性和无害性已与其性能同等重要。然而，现有安全对齐方法常面临安全与性能的权衡，且易受越狱攻击影响，主要因其依赖对恶意查询的直接拒绝。本文提出STAIR框架，将安全对齐与内省推理结合，通过自我改进的链式思维（CoT）推理，使LLMs逐步识别安全风险。STAIR首先赋予模型结构化推理能力，再通过新提出的安全信息蒙特卡洛树搜索（SI-MCTS）生成的步骤级推理数据，进行迭代偏好优化以推进安全对齐。我们进一步训练过程奖励模型，指导测试时搜索以改进响应。实验表明，STAIR有效减少有害输出，同时更好保留有用性，测试时扩展后，STAIR在越狱攻击中达到与Claude-3.5相当的安全性能。相关资源见https://github.com/thu-ml/STAIR。

> Ensuring the safety and harmlessness of Large Language Models (LLMs) has become equally critical as their performance in applications. However, existing safety alignment methods typically suffer from safety-performance trade-offs and the susceptibility to jailbreak attacks, primarily due to their reliance on direct refusals for malicious queries. In this paper, we propose STAIR, a novel framework that integrates SafeTy Alignment with Itrospective Reasoning. We enable LLMs to identify safety risks through step-by-step analysis by self-improving chain-of-thought (CoT) reasoning with safety awareness. STAIR first equips the model with a structured reasoning capability and then advances safety alignment via iterative preference optimization on step-level reasoning data generated using our newly proposed Safety-Informed Monte Carlo Tree Search (SI-MCTS). We further train a process reward model on this data to guide test-time searches for improved responses. Extensive experiments show that STAIR effectively mitigates harmful outputs while better preserving helpfulness, compared to instinctive alignment strategies. With test-time scaling, STAIR achieves a safety performance comparable to Claude-3.5 against popular jailbreak attacks. Relevant resources in this work are available at https://github.com/thu-ml/STAIR.

[Arxiv](https://arxiv.org/abs/2502.02384)