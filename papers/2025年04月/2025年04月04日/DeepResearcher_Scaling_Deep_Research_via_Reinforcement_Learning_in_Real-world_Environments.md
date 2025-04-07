# # DeepResearcher：借助强化学习，在真实环境中实现深度研究的规模化应用

发布时间：2025年04月04日

`Agent` `网络技术`

> DeepResearcher: Scaling Deep Research via Reinforcement Learning in Real-world Environments

# 摘要

> 配备网络搜索能力的大型语言模型（LLMs）在深度研究任务中展现出令人瞩目的潜力。然而，现有方法主要面临两大局限：基于提示工程的方法表现脆弱，而基于检索增强生成（RAG）的强化学习方法又难以应对现实交互的复杂性。本文提出DeepResearcher，首个专注于端到端训练的深度研究代理框架，通过在真实网络环境中扩展强化学习，实现更 robust 的研究能力。与传统RAG方法不同，DeepResearcher突破了固定语料库的限制，使代理能够应对开放网络中信息的噪声、非结构化和动态变化特性。我们设计了一种创新的多代理架构，通过协同工作从复杂网页结构中提取关键信息，并成功克服了多项技术挑战。实验结果显示，DeepResearcher在开放领域研究任务中表现优异，较传统方法提升显著。定性分析进一步揭示了端到端训练带来的认知能力突破，包括自主规划、多源验证、自我反思调整以及诚实表达不确定性等。我们的研究证明，真实网络环境中的端到端训练是开发实用研究能力的核心要素。DeepResearcher已开源，欢迎访问GitHub获取更多信息：https://github.com/GAIR-NLP/DeepResearcher。

> Large Language Models (LLMs) equipped with web search capabilities have demonstrated impressive potential for deep research tasks. However, current approaches predominantly rely on either manually engineered prompts (prompt engineering-based) with brittle performance or reinforcement learning within controlled Retrieval-Augmented Generation (RAG) environments (RAG-based) that fail to capture the complexities of real-world interaction. In this paper, we introduce DeepResearcher, the first comprehensive framework for end-to-end training of LLM-based deep research agents through scaling reinforcement learning (RL) in real-world environments with authentic web search interactions. Unlike RAG-based approaches that assume all necessary information exists within a fixed corpus, our method trains agents to navigate the noisy, unstructured, and dynamic nature of the open web. We implement a specialized multi-agent architecture where browsing agents extract relevant information from various webpage structures and overcoming significant technical challenges. Extensive experiments on open-domain research tasks demonstrate that DeepResearcher achieves substantial improvements of up to 28.9 points over prompt engineering-based baselines and up to 7.2 points over RAG-based RL agents. Our qualitative analysis reveals emergent cognitive behaviors from end-to-end RL training, including the ability to formulate plans, cross-validate information from multiple sources, engage in self-reflection to redirect research, and maintain honesty when unable to find definitive answers. Our results highlight that end-to-end training in real-world web environments is not merely an implementation detail but a fundamental requirement for developing robust research capabilities aligned with real-world applications. We release DeepResearcher at https://github.com/GAIR-NLP/DeepResearcher.

[Arxiv](https://arxiv.org/abs/2504.03160)