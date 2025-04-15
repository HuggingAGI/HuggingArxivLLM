# # 打造认知偏好对齐的小型推理 LLM

发布时间：2025年04月13日

`LLM理论

理由：这篇论文探讨了如何通过新的框架和算法来训练更高效的小型LLMs，重点在于模型训练方法和算法的改进，属于LLM的理论研究。` `人工智能`

> Training Small Reasoning LLMs with Cognitive Preference Alignment

# 摘要

> 大型语言模型（LLMs）如OpenAI的o1和DeepSeek-R1的推理能力已通过深度思考获得显著提升，但这些改进带来了巨大的资源需求。这促使我们探索如何以更少的参数量训练高效推理的LLMs。关键挑战在于，小型模型与大型模型在容量和认知轨迹上存在显著差异，直接蒸馏大型LLMs的思维链（CoT）结果到小型模型往往效果不佳，且需要大量标注数据。本文提出了一种名为Critique-Rethink-Verify（CRV）的新颖框架，旨在训练规模更小但推理能力强大的LLMs。CRV框架由多个具备独特能力的LLM代理组成：根据小型模型的认知能力评估思维链，重新思考并优化这些思维链，以及验证优化结果的正确性。我们还提出了一种认知偏好优化（CogPO）算法，通过将小型模型的思维与它们的认知能力相匹配来提升其推理能力。在具有挑战性的推理基准测试中的全面评估表明，CRV和CogPO的效能显著优于其他训练方法，优势明显。

> The reasoning capabilities of large language models (LLMs), such as OpenAI's o1 and DeepSeek-R1, have seen substantial advancements through deep thinking. However, these enhancements come with significant resource demands, underscoring the need to explore strategies to train effective reasoning LLMs with far fewer parameters. A critical challenge is that smaller models have different capacities and cognitive trajectories than their larger counterparts. Hence, direct distillation of chain-of-thought (CoT) results from large LLMs to smaller ones can be sometimes ineffective and requires a huge amount of annotated data. In this paper, we introduce a novel framework called Critique-Rethink-Verify (CRV), designed for training smaller yet powerful reasoning LLMs. Our CRV framework consists of multiple LLM agents, each specializing in unique abilities: (i) critiquing the CoTs according to the cognitive capabilities of smaller models, (ii) rethinking and refining these CoTs based on the critiques, and (iii) verifying the correctness of the refined results. We further propose the cognitive preference optimization (CogPO) algorithm to enhance the reasoning abilities of smaller models by aligning thoughts of these models with their cognitive capacities. Comprehensive evaluations on challenging reasoning benchmarks demonstrate the efficacy of CRV and CogPO, which outperforms other training methods by a large margin.

[Arxiv](https://arxiv.org/abs/2504.09802)