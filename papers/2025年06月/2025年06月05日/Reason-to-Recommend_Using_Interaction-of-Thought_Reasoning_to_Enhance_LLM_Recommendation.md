# # 推荐的理由：通过思想交互推理机制优化大型语言模型推荐效果

发布时间：2025年06月05日

`LLM应用` `推荐系统` `人工智能`

> Reason-to-Recommend: Using Interaction-of-Thought Reasoning to Enhance LLM Recommendation

# 摘要

> 大型语言模型（LLMs）的突破推动了它们在推荐任务中的应用，因其强大的语义理解和灵活的提示机制。此前研究主要通过将用户-项目交互或元数据编码为提示来进行推荐。与此同时，LLM推理能力在数学和代码等领域表现出色，这得益于测试时缩放和强化学习的提升，这些领域具有清晰的推理轨迹和正确性信号，从而实现了高性能和可解释性。然而，直接将这些推理方法应用于推荐领域效果不佳，因为用户反馈是隐式的，缺乏有效的推理监督。针对这一问题，我们提出了$	extbf{R2Rec}$，一个基于增强推理的推荐框架。该框架通过从用户-项目图中采样交互链，并借助逐步遮蔽的提示策略，将这些链路转化为结构化的交互思维，每个思维代表基于交互上下文的分步推理。这使LLMs能够基于隐式模式模拟逐步决策过程。我们设计了一个两阶段训练管道：首先通过监督微调让模型从高质量轨迹中学习基本推理，然后利用强化学习通过奖励信号优化推理过程，有效缓解了显式监督信号稀疏的问题。在三个真实世界数据集上的实验表明，$	extbf{R2Rec}$在HitRatio@1指标上平均比经典和基于LLM的基线高出$	extbf{10.48\%}$，比原始LLM高出$	extbf{131.81\%}$。此外，显式的推理链路通过揭示决策过程增强了推荐结果的可解释性。我们的代码可在以下链接获取：[https://anonymous.4open.science/r/R2Rec-7C5D](https://anonymous.4open.science/r/R2Rec-7C5D)。


> Driven by advances in Large Language Models (LLMs), integrating them into recommendation tasks has gained interest due to their strong semantic understanding and prompt flexibility. Prior work encoded user-item interactions or metadata into prompts for recommendations. In parallel, LLM reasoning, boosted by test-time scaling and reinforcement learning, has excelled in fields like mathematics and code, where reasoning traces and correctness signals are clear, enabling high performance and interpretability. However, directly applying these reasoning methods to recommendation is ineffective because user feedback is implicit and lacks reasoning supervision. To address this, we propose $\textbf{R2Rec}$, a reasoning-enhanced recommendation framework that samples interaction chains from the user-item graph and converts them into structured interaction-of-thoughts via a progressive masked prompting strategy, with each thought representing stepwise reasoning grounded in interaction context. This allows LLMs to simulate step-by-step decision-making based on implicit patterns. We design a two-stage training pipeline: supervised fine-tuning teaches basic reasoning from high-quality traces, and reinforcement learning refines reasoning via reward signals, alleviating sparse explicit supervision. Experiments on three real-world datasets show R2Rec outperforms classical and LLM-based baselines with an average $\textbf{10.48%}$ improvement in HitRatio@1 and $\textbf{131.81%}$ gain over the original LLM. Furthermore, the explicit reasoning chains enhance interpretability by revealing the decision process. Our code is available at: https://anonymous.4open.science/r/R2Rec-7C5D.

[Arxiv](https://arxiv.org/abs/2506.05069)