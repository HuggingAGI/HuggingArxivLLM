# MMAT-1M：面向多模态智能体微调的大型推理数据集。

发布时间：2025年07月29日

`Agent` `多模态` `智能体调优`

> MMAT-1M: A Large Reasoning Dataset for Multimodal Agent Tuning

# 摘要

> 通过智能体调优增强的大型语言模型（LLMs）在链式思维（CoT）和工具利用方面表现卓越，远超独立模型。然而，多模态领域仍缺乏大规模、高质量的智能体调优数据集，限制了多模态模型潜力的充分发挥。为解决这一问题，我们推出了MMAT-1M——首个支持链式思维、反思和动态工具使用的百万规模多模态智能体调优数据集。我们的数据集通过创新的四阶段数据引擎构建：1) 整理公开多模态数据集中的问答对；2) 借助GPT-4o生成推理过程，并通过多轮范式动态整合API调用和检索增强生成（RAG）信息；3) 通过反思优化推理过程，确保逻辑一致性和准确性，创建包含推理与反思（RR）的多轮对话数据集；4) 为提升效率，可选地将多轮对话压缩为单轮推理与反思（ORR）格式。在MMAT-1M数据集上对开源多模态模型进行微调后，性能显著提升。例如，InternVL2.5-8B-RR模型在八个公开基准测试中平均提升2.7%，在RAG基准测试Dyn-VQA中提升8.8%，充分证明了该数据集在增强多模态推理和工具使用能力方面的有效性。该数据集现已公开，访问地址为https://github.com/VIS-MPU-Agent/MMAT-1M。

> Large Language Models (LLMs), enhanced through agent tuning, have demonstrated remarkable capabilities in Chain-of-Thought (CoT) and tool utilization, significantly surpassing the performance of standalone models. However, the multimodal domain still lacks a large-scale, high-quality agent tuning dataset to unlock the full potential of multimodal large language models. To bridge this gap, we introduce MMAT-1M, the first million-scale multimodal agent tuning dataset designed to support CoT, reflection, and dynamic tool usage. Our dataset is constructed through a novel four-stage data engine: 1) We first curate publicly available multimodal datasets containing question-answer pairs; 2) Then, leveraging GPT-4o, we generate rationales for the original question-answer pairs and dynamically integrate API calls and Retrieval Augmented Generation (RAG) information through a multi-turn paradigm; 3) Furthermore, we refine the rationales through reflection to ensure logical consistency and accuracy, creating a multi-turn dialogue dataset with both Rationale and Reflection (RR); 4) Finally, to enhance efficiency, we optionally compress multi-turn dialogues into a One-turn Rationale and Reflection (ORR) format. By fine-tuning open-source multimodal models on the MMAT-1M, we observe significant performance gains. For instance, the InternVL2.5-8B-RR model achieves an average improvement of 2.7% across eight public benchmarks and 8.8% on the RAG benchmark Dyn-VQA, demonstrating the dataset's effectiveness in enhancing multimodal reasoning and tool-based capabilities. The dataset is publicly available at https://github.com/VIS-MPU-Agent/MMAT-1M.

[Arxiv](https://arxiv.org/abs/2507.21924)