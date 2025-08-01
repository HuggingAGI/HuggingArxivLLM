# GasAgent：智能合约自动气体优化的多智能体框架 GasAgent

发布时间：2025年07月21日

`Agent` `区块链` `智能合约`

> GasAgent: A Multi-Agent Framework for Automated Gas Optimization in Smart Contracts

# 摘要

> 智能合约是区块链上可信、不可变且自动执行的程序。它们的运行依赖于Gas机制以确保效率和公平性。然而，由于非优化的编码实践，许多合约中存在需要优化的Gas浪费模式。现有的解决方案大多依赖人工发现，这种方法不仅效率低下、维护成本高昂，而且难以扩展。最近的研究利用大型语言模型（LLMs）探索新的Gas浪费模式，但这些方法往往难以与现有模式兼容，容易产生冗余模式，并需要人工验证或重写。为了解决这一问题，我们提出了GasAgent——首个结合现有模式兼容性和新模式自动发现与验证功能的智能合约Gas优化多智能体系统，实现端到端优化。GasAgent由四个专门的智能体组成：Seeker、Innovator、Executor和Manager，它们在一个闭环中协作，以识别、验证和应用节省Gas的改进。在100个经过验证的真实合约上的实验表明，GasAgent成功优化了82个合约，平均部署Gas节省了9.97%。此外，我们的评估确认了其与现有工具的兼容性，并通过消融研究验证了每个模块的有效性。为了评估其更广泛的适用性，我们进一步评估了由五种代表性LLMs生成的10个类别的500个合约，并发现GasAgent优化了其中79.8%的合约，部署Gas节省范围在4.79%到13.93%之间，证明了其作为LLM辅助智能合约开发优化层的适用性。

> Smart contracts are trustworthy, immutable, and automatically executed programs on the blockchain. Their execution requires the Gas mechanism to ensure efficiency and fairness. However, due to non-optimal coding practices, many contracts contain Gas waste patterns that need to be optimized. Existing solutions mostly rely on manual discovery, which is inefficient, costly to maintain, and difficult to scale. Recent research uses large language models (LLMs) to explore new Gas waste patterns. However, it struggles to remain compatible with existing patterns, often produces redundant patterns, and requires manual validation/rewriting. To address this gap, we present GasAgent, the first multi-agent system for smart contract Gas optimization that combines compatibility with existing patterns and automated discovery/validation of new patterns, enabling end-to-end optimization. GasAgent consists of four specialized agents, Seeker, Innovator, Executor, and Manager, that collaborate in a closed loop to identify, validate, and apply Gas-saving improvements. Experiments on 100 verified real-world contracts demonstrate that GasAgent successfully optimizes 82 contracts, achieving an average deployment Gas savings of 9.97%. In addition, our evaluation confirms its compatibility with existing tools and validates the effectiveness of each module through ablation studies. To assess broader usability, we further evaluate 500 contracts generated by five representative LLMs across 10 categories and find that GasAgent optimizes 79.8% of them, with deployment Gas savings ranging from 4.79% to 13.93%, showing its usability as the optimization layer for LLM-assisted smart contract development.

[Arxiv](https://arxiv.org/abs/2507.15761)