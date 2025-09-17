# # 基于检索增强框架与大型语言模型（LLMs）的零样本图推理

发布时间：2025年09月16日

`RAG` `基础理论`

> Zero-shot Graph Reasoning via Retrieval Augmented Framework with LLMs

# 摘要

> 我们提出了一种全新的免训练方法——基于检索增强框架的图推理（GRRAF），它借助检索增强生成（RAG）技术与大型语言模型（LLMs）的代码生成能力，可应对各类图推理任务。在GRRAF中，目标图存储于图数据库，LLM通过提示生成可执行代码查询来提取所需信息。该方法规避了现有方法需大量微调或依赖预定义算法的局限，并融入带超时机制的错误反馈循环，兼顾正确性与效率。在GraphInstruct数据集上的实验结果显示，GRRAF在环检测、二分图检查、最短路径计算和最大流等多数图推理任务中准确率达100%，且无论图规模大小，token成本始终稳定。子图匹配任务上性能虽未臻完美但依旧卓越，更值得一提的是，GRRAF能有效扩展至拥有多达10,000个节点的大型图。

> We propose a new, training-free method, Graph Reasoning via Retrieval Augmented Framework (GRRAF), that harnesses retrieval-augmented generation (RAG) alongside the code-generation capabilities of large language models (LLMs) to address a wide range of graph reasoning tasks. In GRRAF, the target graph is stored in a graph database, and the LLM is prompted to generate executable code queries that retrieve the necessary information. This approach circumvents the limitations of existing methods that require extensive finetuning or depend on predefined algorithms, and it incorporates an error feedback loop with a time-out mechanism to ensure both correctness and efficiency. Experimental evaluations on the GraphInstruct dataset reveal that GRRAF achieves 100% accuracy on most graph reasoning tasks, including cycle detection, bipartite graph checks, shortest path computation, and maximum flow, while maintaining consistent token costs regardless of graph sizes. Imperfect but still very high performance is observed on subgraph matching. Notably, GRRAF scales effectively to large graphs with up to 10,000 nodes.

[Arxiv](https://arxiv.org/abs/2509.12743)