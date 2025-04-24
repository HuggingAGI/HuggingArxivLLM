# DMind基准：Web3领域首个全面评估大型语言模型的基准测试

发布时间：2025年04月18日

`LLM应用

理由：这篇论文专注于评估大型语言模型在Web3相关领域的应用表现，通过创建特定的基准测试来分析模型在这些新兴领域的适应性和能力。它属于LLM的应用层面，评估和提升模型在实际场景中的表现。` `Web3` `区块链`

> DMind Benchmark: The First Comprehensive Benchmark for LLM Evaluation in the Web3 Domain

# 摘要

> 大型语言模型的迅猛发展推动了自然语言处理领域的显著进步。然而，它们在Web3等前沿领域的应用潜力尚未得到充分挖掘。本文推出DMind基准测试，这是一个全新的评测框架，系统性地评估了大型语言模型在区块链基础、智能合约分析、DeFi、DAO、NFT、代币经济学、模因概念及安全漏洞等九个关键领域的表现。

DMind基准测试突破了传统选择题的局限，创新性地引入了特定领域的主观任务（如智能合约代码审计与修复、链上数据推理和填空评估），全面反映现实场景的复杂性并深度考验模型的适应能力。我们对包括ChatGPT、DeepSeek、Claude和Gemini系列在内的十五个主流大型语言模型进行了评测，发现这些模型在Web3特定推理和应用领域，特别是在代币经济学和模因概念等新兴领域，仍存在显著性能差距。即便是表现最为突出的模型，在识别细微安全漏洞和解析复杂DeFi机制方面也面临严峻挑战。

为推动这一领域的持续发展，我们公开发布了DMind基准测试的数据集、评估流程和标注结果（访问http://www.dmind.ai），为提升专业领域适应能力、开发更强大的Web3增强型大型语言模型提供了重要参考。

> Recent advances in Large Language Models (LLMs) have led to significant progress on a wide range of natural language processing tasks. However, their effectiveness in specialized and rapidly evolving domains such as Web3 remains underexplored. In this paper, we introduce DMind Benchmark, a novel framework that systematically tests LLMs across nine key categories encompassing blockchain fundamentals, infrastructure, smart contract analysis, decentralized finance (DeFi), decentralized autonomous organizations (DAOs), non-fungible tokens (NFTs), token economics, meme concepts, and security vulnerabilities.
  DMind Benchmark goes beyond conventional multiple-choice questions by incorporating domain-specific subjective tasks (e.g., smart contract code auditing and repair, numeric reasoning on on-chain data, and fill-in assessments), thereby capturing real-world complexities and stress-testing model adaptability. We evaluate fifteen popular LLMs (from ChatGPT, DeepSeek, Claude, and Gemini series) on DMind Benchmark, uncovering performance gaps in Web3-specific reasoning and application, particularly in emerging areas like token economics and meme concepts. Even the strongest models face significant challenges in identifying subtle security vulnerabilities and analyzing complex DeFi mechanisms. To foster progress in this area, we publicly release our benchmark dataset, evaluation pipeline, and annotated results at http://www.dmind.ai, offering a valuable resource for advancing specialized domain adaptation and the development of more robust Web3-enabled LLMs.

[Arxiv](https://arxiv.org/abs/2504.16116)