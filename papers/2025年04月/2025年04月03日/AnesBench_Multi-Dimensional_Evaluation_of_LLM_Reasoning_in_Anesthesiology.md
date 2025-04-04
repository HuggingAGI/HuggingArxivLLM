# AnesBench：麻醉学中LLM推理的多维度评估

发布时间：2025年04月03日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在麻醉学这一专业领域的应用，特别是在推理能力方面的评估。论文中提到的跨语言基准测试AnesBench以及对模型特性、训练策略和推理技术的分析，都属于对LLMs在特定应用领域的研究和优化，因此归类为LLM应用。`

> AnesBench: Multi-Dimensional Evaluation of LLM Reasoning in Anesthesiology

# 摘要

> 大型语言模型（LLMs）在医学领域的应用备受关注，但其在麻醉学等专业领域中的推理能力仍有待深入探索。本文系统性评估了LLMs在麻醉学中的推理能力，并分析了影响其性能的关键因素。为此，我们推出了跨语言基准测试AnesBench，旨在从三个层面评估与麻醉学相关的推理能力：事实检索（System 1）、混合推理（System 1.x）和复杂决策（System 2）。通过大量实验，我们首先研究了模型特性（如模型规模、CoT长度和语言可迁移性）对推理性能的影响。随后，我们利用精心整理的麻醉学相关数据集，评估了持续预训练（CPT）和监督微调（SFT）等不同训练策略的有效性。此外，我们还探讨了测试时推理技术（如Best-of-N采样和束搜索）对推理性能的影响，并评估了推理增强型模型蒸馏（以DeepSeek-R1为例）的作用。我们将在GitHub（https://github.com/MiliLab/AnesBench）公开发布AnesBench基准测试，以及相关的训练数据集和评估代码。


> The application of large language models (LLMs) in the medical field has gained significant attention, yet their reasoning capabilities in more specialized domains like anesthesiology remain underexplored. In this paper, we systematically evaluate the reasoning capabilities of LLMs in anesthesiology and analyze key factors influencing their performance. To this end, we introduce AnesBench, a cross-lingual benchmark designed to assess anesthesiology-related reasoning across three levels: factual retrieval (System 1), hybrid reasoning (System 1.x), and complex decision-making (System 2). Through extensive experiments, we first explore how model characteristics, including model scale, Chain of Thought (CoT) length, and language transferability, affect reasoning performance. Then, we further evaluate the effectiveness of different training strategies, leveraging our curated anesthesiology-related dataset, including continuous pre-training (CPT) and supervised fine-tuning (SFT). Additionally, we also investigate how the test-time reasoning techniques, such as Best-of-N sampling and beam search, influence reasoning performance, and assess the impact of reasoning-enhanced model distillation, specifically DeepSeek-R1. We will publicly release AnesBench, along with our CPT and SFT training datasets and evaluation code at https://github.com/MiliLab/AnesBench.

[Arxiv](https://arxiv.org/abs/2504.02404)