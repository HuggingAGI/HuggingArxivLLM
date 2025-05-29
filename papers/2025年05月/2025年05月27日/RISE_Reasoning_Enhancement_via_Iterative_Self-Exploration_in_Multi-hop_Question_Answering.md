# RISE：通过迭代自我探索增强多跳问答推理能力

发布时间：2025年05月27日

`RAG` `问答系统` `信息检索`

> RISE: Reasoning Enhancement via Iterative Self-Exploration in Multi-hop Question Answering

# 摘要

> 大型语言模型（LLMs）在众多领域表现优异，但在处理复杂推理任务，尤其是多跳问答（MHQA）方面仍具挑战。MHQA需要整合多源证据并处理复杂逻辑依赖，往往导致推理错误。检索增强生成（RAG）虽在MHQA任务中广泛应用，但在有效过滤噪声数据和检索全面证据方面存在局限，影响了其应对MHQA问题的效果。为解决这些问题，我们提出RISE框架：通过迭代自我探索增强推理能力。RISE专为提升模型推理能力而设计，包含三个关键步骤：问题分解、检索后阅读和自我批判。借助持续自我探索，RISE能够识别准确的推理路径，从而迭代优化模型在整合证据、保持逻辑一致性和提升MHQA任务表现方面的能力。在多个MHQA基准测试中，RISE展现了显著的推理准确性和任务性能提升。

> Large Language Models (LLMs) excel in many areas but continue to face challenges with complex reasoning tasks, such as Multi-Hop Question Answering (MHQA). MHQA requires integrating evidence from diverse sources while managing intricate logical dependencies, often leads to errors in reasoning. Retrieval-Augmented Generation (RAG), widely employed in MHQA tasks, faces challenges in effectively filtering noisy data and retrieving all necessary evidence, thereby limiting its effectiveness in addressing MHQA challenges. To address these challenges, we propose RISE:Reasoning Enhancement via Iterative Self-Exploration, a novel framework designed to enhance models' reasoning capability through iterative self-exploration. Specifically, RISE involves three key steps in addressing MHQA tasks: question decomposition, retrieve-then-read, and self-critique. By leveraging continuous self-exploration, RISE identifies accurate reasoning paths, iteratively self-improving the model's capability to integrate evidence, maintain logical consistency, and enhance performance in MHQA tasks. Extensive experiments on multiple MHQA benchmarks demonstrate that RISE significantly improves reasoning accuracy and task performance.

[Arxiv](https://arxiv.org/abs/2505.21940)