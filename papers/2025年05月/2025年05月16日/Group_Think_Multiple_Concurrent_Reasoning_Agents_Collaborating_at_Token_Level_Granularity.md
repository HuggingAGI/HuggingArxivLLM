# 群体思维机制：多个推理代理基于Token级别的粒度进行并发协作

发布时间：2025年05月16日

`LLM应用

理由：这篇论文探讨了如何通过Group Think方案优化大型语言模型的推理过程，属于应用层面的创新，旨在提升推理效率和质量，因此归类为LLM应用。` `人工智能` `推理系统`

> Group Think: Multiple Concurrent Reasoning Agents Collaborating at Token Level Granularity

# 摘要

> 近期研究表明，大型语言模型（LLMs）通过自动生成的思维链展现出强大的推理能力。多个推理代理能够协作，将整体推理质量提升至超越个体表现。然而，这些代理通常以轮流方式交互，以增加延迟换取更好的质量。本文提出了一种名为Group Think的方案，即一个LLM同时扮演多个并发推理代理，或称为思考者。通过共享彼此的部分生成进度，Group Think引入了一种新的并发推理范式，在该范式中，多个推理路径能够在令牌级别动态适应彼此。例如，一个推理线程在检测到另一个线程处于更有利的延续位置时，可能会在句子中间改变生成方向。这种细致入微的、基于令牌级别的协作使Group Think能够减少冗余推理、提升质量，同时实现显著降低延迟。此外，其并发特性使得闲置计算资源得到高效利用，尤其适合边缘推理场景，因为极小的批量大小通常会导致本地GPU利用率低下。我们提供了一种简单且通用的修改方案，使任何现有的LLM都能在本地GPU上实现Group Think。我们还提出了一种评估策略，用于基准测试推理延迟，并通过开源LLMs的实证研究展示了延迟的改进，而这些模型并未明确针对Group Think进行训练。我们希望这项研究为未来LLMs实现更复杂、更高效的协作行为铺平道路，从而生成更高质量的内容。

> Recent advances in large language models (LLMs) have demonstrated the power of reasoning through self-generated chains of thought. Multiple reasoning agents can collaborate to raise joint reasoning quality above individual outcomes. However, such agents typically interact in a turn-based manner, trading increased latency for improved quality. In this paper, we propose Group Think--a single LLM that acts as multiple concurrent reasoning agents, or thinkers. With shared visibility into each other's partial generation progress, Group Think introduces a new concurrent-reasoning paradigm in which multiple reasoning trajectories adapt dynamically to one another at the token level. For example, a reasoning thread may shift its generation mid-sentence upon detecting that another thread is better positioned to continue. This fine-grained, token-level collaboration enables Group Think to reduce redundant reasoning and improve quality while achieving significantly lower latency. Moreover, its concurrent nature allows for efficient utilization of idle computational resources, making it especially suitable for edge inference, where very small batch size often underutilizes local~GPUs. We give a simple and generalizable modification that enables any existing LLM to perform Group Think on a local GPU. We also present an evaluation strategy to benchmark reasoning latency and empirically demonstrate latency improvements using open-source LLMs that were not explicitly trained for Group Think. We hope this work paves the way for future LLMs to exhibit more sophisticated and more efficient collaborative behavior for higher quality generation.

[Arxiv](https://arxiv.org/abs/2505.11107)