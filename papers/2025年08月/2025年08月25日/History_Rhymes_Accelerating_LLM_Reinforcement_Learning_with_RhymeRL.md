# 历史呼应：借助RhymeRL加速LLM强化学习

发布时间：2025年08月25日

`强化学习` `基础理论`

> History Rhymes: Accelerating LLM Reinforcement Learning with RhymeRL

# 摘要

> 随着大型语言模型（LLMs）的飞速发展，强化学习（RL）已成为提升其推理能力的核心技术。与传统预训练方法不同，RL涵盖展开、奖励、训练等多个阶段，因此需要多种角色协同工作。然而，当前RL系统仍存在GPU利用率低的问题，主要源于两点：（1）受测试时扩展影响，展开阶段在整个RL流程中占比过高；（2）同批次展开长度不均衡，导致GPU出现空闲（即气泡）。尽管异步执行、截断等现有方案能部分缓解该问题，却可能以牺牲训练精度为代价换取效率。
  我们的核心发现源于一个此前被忽略的现象：相邻训练轮次的展开响应具有高度相似性。基于这一发现，我们提出了RhymeRL——一个专为LLM设计的RL系统，它通过两项核心创新来加速RL训练。第一，为提升展开生成效率，我们开发了HistoSpec——一种投机解码推理引擎，它借助历史展开token序列的相似性生成精准草稿。第二，为解决展开气泡问题，我们提出了HistoPipe——一种双层调度策略，它利用历史展开分布的相似性平衡各展开工作器的负载。我们在实际生产环境中对RhymeRL进行了评估，结果显示其可扩展性从几十块GPU扩展到数千块。实验表明，RhymeRL在不降低精度、不改变RL范式的前提下，性能较现有方法提升了2.6倍。

> With the rapid advancement of large language models (LLMs), reinforcement learning (RL) has emerged as a pivotal methodology for enhancing the reasoning capabilities of LLMs. Unlike traditional pre-training approaches, RL encompasses multiple stages: rollout, reward, and training, which necessitates collaboration among various worker types. However, current RL systems continue to grapple with substantial GPU underutilization, due to two primary factors: (1) The rollout stage dominates the overall RL process due to test-time scaling; (2) Imbalances in rollout lengths (within the same batch) result in GPU bubbles. While prior solutions like asynchronous execution and truncation offer partial relief, they may compromise training accuracy for efficiency.
  Our key insight stems from a previously overlooked observation: rollout responses exhibit remarkable similarity across adjacent training epochs. Based on the insight, we introduce RhymeRL, an LLM RL system designed to accelerate RL training with two key innovations. First, to enhance rollout generation, we present HistoSpec, a speculative decoding inference engine that utilizes the similarity of historical rollout token sequences to obtain accurate drafts. Second, to tackle rollout bubbles, we introduce HistoPipe, a two-tier scheduling strategy that leverages the similarity of historical rollout distributions to balance workload among rollout workers. We have evaluated RhymeRL within a real production environment, demonstrating scalability from dozens to thousands of GPUs. Experimental results demonstrate that RhymeRL achieves a 2.6x performance improvement over existing methods, without compromising accuracy or modifying the RL paradigm.

[Arxiv](https://arxiv.org/abs/2508.18588)