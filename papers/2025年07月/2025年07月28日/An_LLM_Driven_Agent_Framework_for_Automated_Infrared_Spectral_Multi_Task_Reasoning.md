# ## 大型语言模型驱动的红外光谱多任务推理自动化代理框架

发布时间：2025年07月28日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在红外光谱分析中的实际应用，特别是在低数据条件下的自动解释难题。论文提出了一种基于LLM的端到端代理框架，用于处理红外光谱数据，展示了LLM在科学数据分析中的潜力。因此，它属于LLM应用类别。` `材料科学`

> An LLM Driven Agent Framework for Automated Infrared Spectral Multi Task Reasoning

# 摘要

> 红外光谱技术能快速无损地测量化学和材料特性，但其高维重叠的光谱带给传统化学计量方法带来了巨大挑战。新兴的大型语言模型（LLMs）凭借其强大的泛化和推理能力，为复杂科学工作流程的自动化带来了巨大潜力。然而，LLMs在红外光谱分析中的应用仍处于探索阶段。本研究聚焦于低数据条件下的红外光谱自动解释难题，提出了一种基于LLM的解决方案。我们开发的端到端代理框架集成了结构化知识库、自动预处理、特征提取和多任务推理，形成了一体化处理流程。通过查询精选的红外光谱文献语料库，代理能够智能选择科学验证的处理方法。这些方法将光谱转化为低维特征，并通过少量样本提示模板实现分类、回归和异常检测。闭环多轮协议通过迭代优化提示内容，显著提升了预测精度。在图章垫墨水、中药、普洱茶、枳壳和废水COD等多种材料数据集上，多轮LLM的表现超越了单轮推理，并在低数据条件下与传统机器学习和深度学习模型相媲美甚至更优。

> Infrared spectroscopy offers rapid, non destructive measurement of chemical and material properties but suffers from high dimensional, overlapping spectral bands that challenge conventional chemometric approaches. Emerging large language models (LLMs), with their capacity for generalization and reasoning, offer promising potential for automating complex scientific workflows. Despite this promise, their application in IR spectral analysis remains largely unexplored. This study addresses the critical challenge of achieving accurate, automated infrared spectral interpretation under low-data conditions using an LLM-driven framework. We introduce an end-to-end, large language model driven agent framework that integrates a structured literature knowledge base, automated spectral preprocessing, feature extraction, and multi task reasoning in a unified pipeline. By querying a curated corpus of peer reviewed IR publications, the agent selects scientifically validated routines. The selected methods transform each spectrum into low dimensional feature sets, which are fed into few shot prompt templates for classification, regression, and anomaly detection. A closed loop, multi turn protocol iteratively appends mispredicted samples to the prompt, enabling dynamic refinement of predictions. Across diverse materials: stamp pad ink, Chinese medicine, Pu'er tea, Citri Reticulatae Pericarpium and waste water COD datasets, the multi turn LLM consistently outperforms single turn inference, rivaling or exceeding machine learning and deep learning models under low data regimes.

[Arxiv](https://arxiv.org/abs/2507.21471)