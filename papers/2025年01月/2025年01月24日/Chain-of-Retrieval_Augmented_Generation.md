# 链式检索增强生成

发布时间：2025年01月24日

`RAG

理由：这篇论文主要讨论了一种改进的RAG（Retrieval-Augmented Generation）方法，称为CoRAG（链式检索增强生成）。该方法通过逐步检索和推理相关信息来生成最终答案，相比传统RAG方法在复杂查询处理上表现更好。论文的核心内容围绕RAG模型的改进和应用展开，因此应归类为RAG。` `问答系统`

> Chain-of-Retrieval Augmented Generation

# 摘要

> 本文提出了一种训练类似o1的RAG模型的方法，该模型在生成最终答案前逐步检索和推理相关信息。传统RAG方法通常在生成前仅执行一次检索，由于检索结果不完美，处理复杂查询时效果有限。相比之下，我们提出的CoRAG（链式检索增强生成）方法允许模型根据状态动态调整查询。为有效训练CoRAG，我们利用拒绝采样自动生成中间检索链，从而增强仅提供最终答案的现有RAG数据集。测试时，我们提出多种解码策略，通过控制检索链的长度和数量来扩展模型的计算能力。多个基准测试的实验结果验证了CoRAG的有效性，特别是在多跳问答任务中，EM分数比强基线提高了10分以上。在KILT基准测试中，CoRAG在多种知识密集型任务中达到了新的最先进水平。此外，我们提供了全面分析，为未来开发事实和基础模型的研究奠定了基础。

> This paper introduces an approach for training o1-like RAG models that retrieve and reason over relevant information step by step before generating the final answer. Conventional RAG methods usually perform a single retrieval step before the generation process, which limits their effectiveness in addressing complex queries due to imperfect retrieval results. In contrast, our proposed method, CoRAG (Chain-of-Retrieval Augmented Generation), allows the model to dynamically reformulate the query based on the evolving state. To train CoRAG effectively, we utilize rejection sampling to automatically generate intermediate retrieval chains, thereby augmenting existing RAG datasets that only provide the correct final answer. At test time, we propose various decoding strategies to scale the model's test-time compute by controlling the length and number of sampled retrieval chains. Experimental results across multiple benchmarks validate the efficacy of CoRAG, particularly in multi-hop question answering tasks, where we observe more than 10 points improvement in EM score compared to strong baselines. On the KILT benchmark, CoRAG establishes a new state-of-the-art performance across a diverse range of knowledge-intensive tasks. Furthermore, we offer comprehensive analyses to understand the scaling behavior of CoRAG, laying the groundwork for future research aimed at developing factual and grounded foundation models.

[Arxiv](https://arxiv.org/abs/2501.14342)