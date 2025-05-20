# 利用奖励引导的树形搜索提升大型语言模型在知识图谱问答中的表现

发布时间：2025年05月18日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在知识图谱问答（KGQA）任务中的应用，并提出了一种新的无训练框架RTSoG来改进现有方法。虽然它涉及检索增强生成（RAG）的概念，但主要焦点是应用层面的改进和优化，因此归类为LLM应用。` `知识图谱` `问答系统`

> Enhancing Large Language Models with Reward-guided Tree Search for Knowledge Graph Question and Answering

# 摘要

> 近年来，大型语言模型（LLMs）在知识图谱问答（KGQA）任务中表现卓越，该任务旨在通过知识图谱（KGs）为自然语言问题提供答案。现有的基于LLMs的KGQA方法通常遵循图检索增强生成（GraphRAG）范式，即先从大规模KGs中检索推理路径，再基于这些路径生成答案。然而，这些方法在KG中过分强调探索新的最优推理路径，而忽视了对历史推理路径的利用，可能导致次优推理路径的出现。此外，问题中的复杂语义可能导致检索到不准确的推理路径。为了解决这些问题，本文提出了一种名为RTSoG的新型无训练框架。RTSoG通过将原始问题分解为一系列更简单且定义明确的子问题来处理复杂的语义。然后，引入了一种由奖励模型引导的自我批评蒙特卡洛树搜索（SC-MCTS），用于迭代检索加权推理路径作为上下文知识。最后，根据权重堆叠加权推理路径以生成最终答案。在四个数据集上的广泛实验验证了RTSoG的有效性。值得注意的是，与最先进的方法相比，RTSoG在GrailQA和WebQSP上分别实现了8.7%和7.0%的性能提升。

> Recently, large language models (LLMs) have demonstrated impressive performance in Knowledge Graph Question Answering (KGQA) tasks, which aim to find answers based on knowledge graphs (KGs) for natural language questions. Existing LLMs-based KGQA methods typically follow the Graph Retrieval-Augmented Generation (GraphRAG) paradigm, which first retrieves reasoning paths from the large KGs, and then generates the answers based on them. However, these methods emphasize the exploration of new optimal reasoning paths in KGs while ignoring the exploitation of historical reasoning paths, which may lead to sub-optimal reasoning paths. Additionally, the complex semantics contained in questions may lead to the retrieval of inaccurate reasoning paths. To address these issues, this paper proposes a novel and training-free framework for KGQA tasks called Reward-guided Tree Search on Graph (RTSoG). RTSoG decomposes an original question into a series of simpler and well-defined sub-questions to handle the complex semantics. Then, a Self-Critic Monte Carlo Tree Search (SC-MCTS) guided by a reward model is introduced to iteratively retrieve weighted reasoning paths as contextual knowledge. Finally, it stacks the weighted reasoning paths according to their weights to generate the final answers. Extensive experiments on four datasets demonstrate the effectiveness of RTSoG. Notably, it achieves 8.7\% and 7.0\% performance improvement over the state-of-the-art method on the GrailQA and the WebQSP respectively.

[Arxiv](https://arxiv.org/abs/2505.12476)