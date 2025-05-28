# SynLogic：通过大规模合成可验证推理数据，助力逻辑推理学习及更广泛领域的探索

发布时间：2025年05月26日

`LLM应用` `数据科学`

> SynLogic: Synthesizing Verifiable Reasoning Data at Scale for Learning Logical Reasoning and Beyond

# 摘要

> 近期，OpenAI-o1 和 DeepSeek R1 等进展展示了强化学习（RL）在提升大型语言模型（LLMs）推理能力方面的潜力。尽管开源社区的复制工作主要集中在数学和编程领域，但开发通用推理能力的方法和资源仍鲜有探索。这一差距部分源于收集适合 RL 的多样化且可验证推理数据的挑战。我们假设逻辑推理对开发通用推理能力至关重要，因为逻辑是推理的基本构建模块。在本研究中，我们介绍了 SynLogic，这是一个生成大规模多样化逻辑推理数据的数据合成框架和数据集，涵盖 35 个不同的逻辑推理任务。SynLogic 方法支持以可控方式合成数据，难度和数量均可调节。重要的是，所有示例均可通过简单规则验证，使其非常适合用于具有可验证奖励的强化学习。在我们的实验中，基于 7B 和 32B 模型，我们在 SynLogic 数据集上验证了 RL 训练的有效性。SynLogic 在开源数据集中实现了最先进的逻辑推理性能，在 BBEH 上比 DeepSeek-R1-Distill-Qwen-32B 高出 6 个百分点。此外，将 SynLogic 数据与数学和编程任务混合使用，可以提高这些领域的训练效率，并显著增强推理的泛化能力。值得注意的是，我们的混合训练模型在多个基准测试中优于 DeepSeek-R1-Zero-Qwen-32B。这些发现确立了 SynLogic 作为提升 LLM 广泛推理能力的宝贵资源。我们开源了数据合成管道和 SynLogic 数据集，地址为 https://github.com/MiniMax-AI/SynLogic。


> Recent advances such as OpenAI-o1 and DeepSeek R1 have demonstrated the potential of Reinforcement Learning (RL) to enhance reasoning abilities in Large Language Models (LLMs). While open-source replication efforts have primarily focused on mathematical and coding domains, methods and resources for developing general reasoning capabilities remain underexplored. This gap is partly due to the challenge of collecting diverse and verifiable reasoning data suitable for RL. We hypothesize that logical reasoning is critical for developing general reasoning capabilities, as logic forms a fundamental building block of reasoning. In this work, we present SynLogic, a data synthesis framework and dataset that generates diverse logical reasoning data at scale, encompassing 35 diverse logical reasoning tasks. The SynLogic approach enables controlled synthesis of data with adjustable difficulty and quantity. Importantly, all examples can be verified by simple rules, making them ideally suited for RL with verifiable rewards. In our experiments, we validate the effectiveness of RL training on the SynLogic dataset based on 7B and 32B models. SynLogic leads to state-of-the-art logical reasoning performance among open-source datasets, surpassing DeepSeek-R1-Distill-Qwen-32B by 6 points on BBEH. Furthermore, mixing SynLogic data with mathematical and coding tasks improves the training efficiency of these domains and significantly enhances reasoning generalization. Notably, our mixed training model outperforms DeepSeek-R1-Zero-Qwen-32B across multiple benchmarks. These findings position SynLogic as a valuable resource for advancing the broader reasoning capabilities of LLMs. We open-source both the data synthesis pipeline and the SynLogic dataset at https://github.com/MiniMax-AI/SynLogic.

[Arxiv](https://arxiv.org/abs/2505.19641)