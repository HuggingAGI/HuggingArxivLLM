# Eliza: 专为 Web3 打造的 AI 代理操作系统

发布时间：2025年01月12日

`Agent

理由：这篇论文主要讨论的是以大型语言模型（LLMs）为认知核心的AI Agent，特别是提出了一个名为Eliza的开源智能体框架，该框架能够无缝集成web3应用。论文的核心内容围绕AI Agent的设计、实现和应用展开，因此应归类为Agent。` `人工智能` `区块链`

> Eliza: A Web3 friendly AI Agent Operating System

# 摘要

> # AI Agent
以大型语言模型（LLMs）为认知核心的AI Agent，是一种能够在用户指令下自主控制执行路径的智能体系统。随着LLMs及其插件（如RAG、文本到图像/视频/3D等）能力的飞速发展，AI Agents的潜力被极大释放，能力日益强大。然而，在AI与web3的交汇处，目前尚缺乏一个理想的智能体框架，能够无缝集成web3应用。本文提出的Eliza，是首个开源且兼容web3的智能体框架，使web3应用的部署变得轻松自如。Eliza的每个部分都是用户完全掌控的常规Typescript程序，并与web3无缝集成（如读写区块链数据、与智能合约交互等）。我们还展示了如何通过Eliza运行时的关键组件实现稳定性能。代码已开源：https://github.com/ai16z/eliza。

> AI Agent, powered by large language models (LLMs) as its cognitive core, is an intelligent agentic system capable of autonomously controlling and determining the execution paths under user's instructions. With the burst of capabilities of LLMs and various plugins, such as RAG, text-to-image/video/3D, etc., the potential of AI Agents has been vastly expanded, with their capabilities growing stronger by the day. However, at the intersection between AI and web3, there is currently no ideal agentic framework that can seamlessly integrate web3 applications into AI agent functionalities. In this paper, we propose Eliza, the first open-source web3-friendly Agentic framework that makes the deployment of web3 applications effortless. We emphasize that every aspect of Eliza is a regular Typescript program under the full control of its user, and it seamlessly integrates with web3 (i.e., reading and writing blockchain data, interacting with smart contracts, etc.). Furthermore, we show how stable performance is achieved through the pragmatic implementation of the key components of Eliza's runtime. Our code is publicly available at https://github.com/ai16z/eliza.

[Arxiv](https://arxiv.org/abs/2501.06781)