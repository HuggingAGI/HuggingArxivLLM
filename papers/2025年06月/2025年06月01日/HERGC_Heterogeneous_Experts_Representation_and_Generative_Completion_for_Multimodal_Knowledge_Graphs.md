# # HERGC：异质专家表示方法与多模态知识图谱的生成式补全

发布时间：2025年06月01日

`LLM应用` `知识图谱` `知识图谱补全`

> HERGC: Heterogeneous Experts Representation and Generative Completion for Multimodal Knowledge Graphs

# 摘要

> 多模态知识图谱（MMKGs）通过整合图像、文本等多种模态，扩展了传统知识图谱（KGs）的表达能力。多模态知识图谱补全（MMKGC）的目标是利用这些异构信息推断缺失的事实，从而弥补MMKGs的不完整性。然而，现有方法通常基于闭世界假设，仅利用MMKGs内部的信息，并采用判别式训练目标，这限制了它们的推理能力。尽管生成式方法在单模态知识图谱补全中表现出色，但其在MMKGC中的应用尚未得到充分探索。为此，我们提出了HERGC框架，通过异构专家表示和生成式补全，有效提升了MMKGs的补全效果。该框架首先利用异构专家表示检索器融合多模态信息，生成紧凑的候选集，再通过微调的生成式LLM预测器精准识别正确答案。实验结果表明，HERGC在三个标准基准上均表现出色，达到了当前最优水平。

> Multimodal knowledge graphs (MMKGs) enrich traditional knowledge graphs (KGs) by incorporating diverse modalities such as images and text. Multi-modal knowledge graph completion (MMKGC) seeks to exploit these heterogeneous signals to infer missing facts, thereby mitigating the intrinsic incompleteness of MMKGs. Existing MMKGC methods typically leverage only the information contained in the MMKGs under the closed-world assumption and adopt discriminative training objectives, which limits their reasoning capacity during completion. Recent generative completion approaches powered by advanced large language models (LLMs) have shown strong reasoning abilities in unimodal knowledge graph completion, but their potential in MMKGC remains largely unexplored. To bridge this gap, we propose HERGC, a Heterogeneous Experts Representation and Generative Completion framework for MMKGs. HERGC first deploys a Heterogeneous Experts Representation Retriever that enriches and fuses multimodal information and retrieves a compact candidate set for each incomplete triple. It then uses a Generative LLM Predictor fine-tuned on minimal instruction data to accurately identify the correct answer from these candidates. Extensive experiments on three standard MMKG benchmarks demonstrate HERGC's effectiveness and robustness, achieving state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2506.00826)