# # 知识图谱与大型语言模型的融合之道
知识图谱如何融入大型语言模型

发布时间：2025年05月12日

`LLM应用

LLM应用` `符号推理` `知识图谱`

> Injecting Knowledge Graphs into Large Language Models

# 摘要

> 将知识图谱（KGs）中的结构化知识融入大型语言模型（LLMs）一直是符号推理领域的重要挑战。现有的方法主要依赖提示工程或微调，但这些方法要么导致结构信息的丢失，要么带来高昂的计算成本。我们基于近期的编码技术，将图嵌入作为标记整合到LLM的输入中，并通过引入知识图谱嵌入（KGE）模型，成功将这一范式扩展至KG领域，从而实现对图结构的感知推理。我们的方法具有模型不可知性、资源高效性和广泛的LLM兼容性。通过在合成和真实世界数据集上的大量实验，结果表明，与现有基准相比，我们的方法显著提升了推理性能，并在准确性和效率方面实现了最优平衡，甚至超越了当前最先进的LLMs.

> Integrating structured knowledge from Knowledge Graphs (KGs) into Large Language Models (LLMs) remains a key challenge for symbolic reasoning. Existing methods mainly rely on prompt engineering or fine-tuning, which lose structural fidelity or incur high computational costs. Building on recent encoding techniques which integrate graph embeddings within the LLM input as tokens, we extend this paradigm to the KG domain by leveraging Knowledge Graph Embedding (KGE) models, thus enabling graph-aware reasoning. Our approach is model-agnostic, resource-efficient, and compatible with any LLMs. Extensive experimentation on synthetic and real-world datasets shows that our method improves reasoning performance over established baselines, further achieving the best trade-off in terms of accuracy and efficiency against state-of-the-art LLMs.

[Arxiv](https://arxiv.org/abs/2505.07554)