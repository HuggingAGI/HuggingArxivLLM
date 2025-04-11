# 大语言模型推理与AI智能体的吞吐量最优调度算法

发布时间：2025年04月09日

`LLM应用` `人工智能` `计算机系统`

> Throughput-Optimal Scheduling Algorithms for LLM Inference and AI Agents

# 摘要

> 随着大型语言模型（LLMs）和AI代理需求的快速增长，优化系统以实现高效的LLM推理变得至关重要。尽管系统级工程方面已经付出了巨大努力，但通过数学建模和排队论视角进行的研究却鲜有探索。
    在本文中，我们致力于为LLM推理系统奠定排队论基础，架起排队论与LLM系统社区之间的桥梁。特别地，我们研究了LLM推理系统中的吞吐量方面。我们证明了一大类'工作保存'调度算法能够实现单个请求和AI代理工作负载的最大吞吐量，突显了'工作保存'作为实践中关键设计原则的重要性。对实际系统的评估表明，Orca和Sarathi-serve是吞吐量最优的，这令从业者倍感欣慰，而FastTransformer和原版vLLM则并非最大稳定，使用时需谨慎。
    我们的研究成果凸显了排队论社区在提升LLM推理系统方面的巨大贡献，并呼吁更多跨学科的发展。

> As demand for Large Language Models (LLMs) and AI agents rapidly grows, optimizing systems for efficient LLM inference becomes critical. While significant efforts have targeted system-level engineering, little is explored through a mathematical modeling and queuing perspective.
  In this paper, we aim to develop the queuing fundamentals for LLM inference, bridging the gap between queuing and LLM system communities. In particular, we study the throughput aspect in LLM inference systems. We prove that a large class of 'work-conserving' scheduling algorithms can achieve maximum throughput for both individual requests and AI agent workloads, highlighting 'work-conserving' as a key design principle in practice. Evaluations of real-world systems show that Orca and Sarathi-serve are throughput-optimal, reassuring practitioners, while FastTransformer and vanilla vLLM are not maximally stable and should be used with caution.
  Our results highlight the substantial benefits queuing community can offer in improving LLM inference systems and call for more interdisciplinary developments.

[Arxiv](https://arxiv.org/abs/2504.07347)