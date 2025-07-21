# AGENTS-LLM：智能体增强型LLM生成具有挑战性的交通场景——基于智能体LLM框架

发布时间：2025年07月18日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）来生成和增强自动驾驶规划器的测试场景。虽然提到了代理（agent）的概念，但核心是将LLM应用于解决自动驾驶中的实际问题，属于LLM的应用场景。` `自动驾驶`

> AGENTS-LLM: Augmentative GENeration of Challenging Traffic Scenarios with an Agentic LLM Framework

# 摘要

> 罕见但关键的场景在自动驾驶规划器的测试与评估中构成重大挑战。仅依赖真实驾驶场景需收集海量数据，而基于LLMs的场景自动生成虽有潜力，却面临数据需求大、输出控制难等问题。从零生成新场景可能导致分布偏移，影响学习型规划器评估效果。近期研究通过增强测试集中的原始场景来生成更具挑战性的案例，但这种方法依赖领域专家手动操作，难以满足自动驾驶系统评估的规模需求。为此，本文提出了一种基于LLM代理的新框架，利用自然语言描述增强现实世界交通场景，有效克服现有方法的局限。创新点在于采用代理式设计，实现对输出的精细控制，即便使用规模较小的LLMs也能保持高性能。大量专家评估表明，本框架能准确捕捉用户意图，生成高质量增强场景，其效果可媲美人工创建。


> Rare, yet critical, scenarios pose a significant challenge in testing and evaluating autonomous driving planners. Relying solely on real-world driving scenes requires collecting massive datasets to capture these scenarios. While automatic generation of traffic scenarios appears promising, data-driven models require extensive training data and often lack fine-grained control over the output. Moreover, generating novel scenarios from scratch can introduce a distributional shift from the original training scenes which undermines the validity of evaluations especially for learning-based planners. To sidestep this, recent work proposes to generate challenging scenarios by augmenting original scenarios from the test set. However, this involves the manual augmentation of scenarios by domain experts. An approach that is unable to meet the demands for scale in the evaluation of self-driving systems. Therefore, this paper introduces a novel LLM-agent based framework for augmenting real-world traffic scenarios using natural language descriptions, addressing the limitations of existing methods. A key innovation is the use of an agentic design, enabling fine-grained control over the output and maintaining high performance even with smaller, cost-effective LLMs. Extensive human expert evaluation demonstrates our framework's ability to accurately adhere to user intent, generating high quality augmented scenarios comparable to those created manually.

[Arxiv](https://arxiv.org/abs/2507.13729)