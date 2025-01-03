# GraphTeam: 多智能体协作助力基于大语言模型的图分析

发布时间：2024年10月23日

`Agent

理由：这篇论文提出了一个基于LLM的多智能体系统——GraphTeam，用于图分析。该系统由多个智能体组成，这些智能体能够协作解决复杂问题，并且利用了外部知识检索和问题解决模块。这种多智能体系统的设计和应用属于Agent领域的研究范畴。` `社交网络` `城市计算`

> GraphTeam: Facilitating Large Language Model-based Graph Analysis via Multi-Agent Collaboration

# 摘要

> # 摘要
图在现实世界中广泛应用于建模关系数据，如社交网络和城市计算。现有的基于LLM的图分析方法要么将图神经网络（GNNs）集成到特定任务中，限制了其可迁移性，要么仅依赖LLM的内部推理能力，导致性能不佳。为解决这些问题，我们借鉴了基于LLM的智能体的最新进展，这些智能体能够利用外部知识或工具解决问题。通过模拟人类解决问题的策略，如类比和协作，我们提出了一个基于LLM的多智能体系统——GraphTeam，用于图分析。GraphTeam由三个模块的五个智能体组成，这些智能体各有所长，能够协作解决复杂问题。具体来说，（1）输入输出归一化模块：问题智能体从原始问题中提取并精炼四个关键参数，促进问题理解，答案智能体则组织结果以满足输出要求；（2）外部知识检索模块：我们构建了一个包含相关文档和经验的知识库，搜索智能体为每个问题检索最相关的条目；（3）问题解决模块：编码智能体利用检索到的信息通过编程生成解决方案，若编码智能体无法工作，推理智能体将直接计算结果。在六个图分析基准上的实验表明，GraphTeam在准确性上比最佳基线平均提升了25.85%，达到了最先进的性能。代码和数据可在https://github.com/BUPT-GAMMA/GraphTeam获取。

> Graphs are widely used for modeling relational data in real-world scenarios, such as social networks and urban computing. Existing LLM-based graph analysis approaches either integrate graph neural networks (GNNs) for specific machine learning tasks, limiting their transferability, or rely solely on LLMs' internal reasoning ability, resulting in suboptimal performance. To address these limitations, we take advantage of recent advances in LLM-based agents, which have shown capabilities of utilizing external knowledge or tools for problem solving. By simulating human problem-solving strategies such as analogy and collaboration, we propose a multi-agent system based on LLMs named GraphTeam, for graph analysis. GraphTeam consists of five LLM-based agents from three modules, and the agents with different specialities can collaborate with each other to address complex problems. Specifically, (1) input-output normalization module: the question agent extracts and refines four key arguments from the original question, facilitating the problem understanding, and the answer agent organizes the results to meet the output requirement; (2) external knowledge retrieval module: we first build a knowledge base consisting of relevant documentation and experience information, and then the search agent retrieves the most relevant entries for each question. (3) problem-solving module: given the retrieved information from search agent, the coding agent uses established algorithms via programming to generate solutions, and in case the coding agent does not work, the reasoning agent will directly compute the results without programming. Extensive experiments on six graph analysis benchmarks demonstrate that GraphTeam achieves state-of-the-art performance with an average 25.85% improvement over the best baseline in terms of accuracy. The code and data are available at https://github.com/BUPT-GAMMA/GraphTeam.

[Arxiv](https://arxiv.org/abs/2410.18032)