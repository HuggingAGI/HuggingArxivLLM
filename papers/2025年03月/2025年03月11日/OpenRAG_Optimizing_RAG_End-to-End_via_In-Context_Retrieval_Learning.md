# # OpenRAG：通过上下文检索学习实现 RAG 的端到端优化

发布时间：2025年03月11日

`RAG` `信息检索` `问答系统`

> OpenRAG: Optimizing RAG End-to-End via In-Context Retrieval Learning

# 摘要

> 本文分析发现，传统信息检索场景中学习到的相关性在RAG场景中可能并不适用。为解决这一问题，我们提出了一种名为OpenRAG的RAG框架，通过端到端优化检索器以捕捉上下文相关性，从而更好地适应多样化需求。实验结果显示，OpenRAG相较于原检索器性能提升4.0%，显著超越现有最优检索器2.1%。值得注意的是，针对部分任务，仅需一个0.2B规模的端到端调整检索器即可超越专门优化的RAG或8B规模指令微调大模型，充分体现了我们的方法在提升RAG系统性能方面的成本效益。

> In this paper, we analyze and empirically show that the learned relevance for conventional information retrieval (IR) scenarios may be inconsistent in retrieval-augmented generation (RAG) scenarios. To bridge this gap, we introduce OpenRAG, a RAG framework that is optimized end-to-end by tuning the retriever to capture in-context relevance, enabling adaptation to the diverse and evolving needs. Extensive experiments across a wide range of tasks demonstrate that OpenRAG, by tuning a retriever end-to-end, leads to a consistent improvement of 4.0% over the original retriever, consistently outperforming existing state-of-the-art retrievers by 2.1%. Additionally, our results indicate that for some tasks, an end-to-end tuned 0.2B retriever can achieve improvements that surpass those of RAG-oriented or instruction-tuned 8B large language models (LLMs), highlighting the cost-effectiveness of our approach in enhancing RAG systems.

[Arxiv](https://arxiv.org/abs/2503.08398)