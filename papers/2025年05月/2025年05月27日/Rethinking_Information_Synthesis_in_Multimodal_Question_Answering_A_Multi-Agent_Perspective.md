# 多模态问答中的信息合成：重新思考 —— 一个多智能体视角

发布时间：2025年05月27日

`Agent` `问答系统` `多模态`

> Rethinking Information Synthesis in Multimodal Question Answering A Multi-Agent Perspective

# 摘要

> 多模态问答技术的最新进展主要集中在结合异质模态或微调多模态大型语言模型。尽管这些方法表现出色，但它们通常依赖单一的通用推理策略，忽视了每种模态的独特特性，导致准确性和可解释性受限。为了解决这些问题，我们提出了一种名为MAMMQA的多智能体问答框架，支持文本、表格和图像等多种模态输入。该系统由两个视觉语言模型（VLM）代理和一个基于文本的大型语言模型（LLM）代理组成。第一个VLM将用户查询分解为子问题，并从各个模态中依次检索部分答案。第二个VLM则通过跨模态推理综合并精炼这些结果。最后，LLM将这些见解整合成一个连贯的答案。这种模块化设计不仅通过透明的推理过程提升了可解释性，还让每个代理在其专业领域内发挥最佳效能。实验结果表明，在多样化多模态问答基准测试中，我们的多智能体框架在准确性和鲁棒性方面均优于现有方法。

> Recent advances in multimodal question answering have primarily focused on combining heterogeneous modalities or fine-tuning multimodal large language models. While these approaches have shown strong performance, they often rely on a single, generalized reasoning strategy, overlooking the unique characteristics of each modality ultimately limiting both accuracy and interpretability. To address these limitations, we propose MAMMQA, a multi-agent QA framework for multimodal inputs spanning text, tables, and images. Our system includes two Visual Language Model (VLM) agents and one text-based Large Language Model (LLM) agent. The first VLM decomposes the user query into sub-questions and sequentially retrieves partial answers from each modality. The second VLM synthesizes and refines these results through cross-modal reasoning. Finally, the LLM integrates the insights into a cohesive answer. This modular design enhances interpretability by making the reasoning process transparent and allows each agent to operate within its domain of expertise. Experiments on diverse multimodal QA benchmarks demonstrate that our cooperative, multi-agent framework consistently outperforms existing baselines in both accuracy and robustness.

[Arxiv](https://arxiv.org/abs/2505.20816)