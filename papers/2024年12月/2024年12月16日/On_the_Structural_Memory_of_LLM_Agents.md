# 论 LLM 智能体的结构记忆

发布时间：2024年12月16日

`Agent` `语言模型` `内存系统`

> On the Structural Memory of LLM Agents

# 摘要

> 内存对于基于大型语言模型（LLM）的代理能够参与诸如问答（QA）和对话系统之类的复杂且长期的交互起着关键作用。尽管针对这些任务已提出了各种各样的内存模块，然而不同内存结构在不同任务中的影响仍未得到充分探究。本文探讨了内存结构和内存检索方法对基于 LLM 的代理性能的影响。具体来说，我们评估了包括块、知识三元组、原子事实和摘要在内的四种内存结构，以及将这些组件相结合的混合内存。另外，我们还评估了三种被广泛使用的内存检索方法：单步检索、重新排序和迭代检索。通过在四个任务和六个数据集上进行的大量实验，得出了以下关键见解：（1）不同的内存结构具有各自的优势，能够适配特定任务；（2）混合内存结构在嘈杂环境中展现出显著的适应性；（3）迭代检索在各种场景中始终优于其他方法。我们的研究旨在推动基于 LLM 的代理的内存系统设计的进一步探索。

> Memory plays a pivotal role in enabling large language model~(LLM)-based agents to engage in complex and long-term interactions, such as question answering (QA) and dialogue systems. While various memory modules have been proposed for these tasks, the impact of different memory structures across tasks remains insufficiently explored. This paper investigates how memory structures and memory retrieval methods affect the performance of LLM-based agents. Specifically, we evaluate four types of memory structures, including chunks, knowledge triples, atomic facts, and summaries, along with mixed memory that combines these components. In addition, we evaluate three widely used memory retrieval methods: single-step retrieval, reranking, and iterative retrieval. Extensive experiments conducted across four tasks and six datasets yield the following key insights: (1) Different memory structures offer distinct advantages, enabling them to be tailored to specific tasks; (2) Mixed memory structures demonstrate remarkable resilience in noisy environments; (3) Iterative retrieval consistently outperforms other methods across various scenarios. Our investigation aims to inspire further research into the design of memory systems for LLM-based agents.

[Arxiv](https://arxiv.org/abs/2412.15266)