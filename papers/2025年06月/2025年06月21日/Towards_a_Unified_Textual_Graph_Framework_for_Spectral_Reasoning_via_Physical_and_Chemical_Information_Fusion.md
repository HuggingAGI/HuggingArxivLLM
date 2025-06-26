# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月21日

`LLM应用` `频谱分析`

> Towards a Unified Textual Graph Framework for Spectral Reasoning via Physical and Chemical Information Fusion

# 摘要

> 为了解决现有频谱分析方法的局限性——如单一模态数据依赖、泛化能力不足和解释性差——我们提出了一种结合先验知识图谱与大型语言模型的多模态频谱分析框架。该方法通过统一的文本图格式，将物理频谱测量与化学结构语义显式关联，实现了灵活、可解释且通用的频谱理解。具体而言，原始频谱首先转换为文本图（TAGs），节点和边携带描述频谱特性和化学背景的文本属性。随后，结合功能基团和分子图等先验知识，形成包含支持LLM上下文推理的“提示节点”的任务图。图神经网络进一步处理该结构以完成下游任务。这种设计实现了多模态的无缝整合和自动化特征解码，且仅需少量手动标注。在节点级、边级和图级分类等任务中，我们的框架表现出色，并在零样本和少样本场景下均具备强大的泛化能力，展示了其在有限数据学习和上下文推理中的优势。这项工作为基于LLM的频谱分析提供了可扩展且可解释的基础，统一了物理与化学模态，助力科学应用。

> Motivated by the limitations of current spectral analysis methods-such as reliance on single-modality data, limited generalizability, and poor interpretability-we propose a novel multi-modal spectral analysis framework that integrates prior knowledge graphs with Large Language Models. Our method explicitly bridges physical spectral measurements and chemical structural semantics by representing them in a unified Textual Graph format, enabling flexible, interpretable, and generalizable spectral understanding. Raw spectra are first transformed into TAGs, where nodes and edges are enriched with textual attributes describing both spectral properties and chemical context. These are then merged with relevant prior knowledge-including functional groups and molecular graphs-to form a Task Graph that incorporates "Prompt Nodes" supporting LLM-based contextual reasoning. A Graph Neural Network further processes this structure to complete downstream tasks. This unified design enables seamless multi-modal integration and automated feature decoding with minimal manual annotation. Our framework achieves consistently high performance across multiple spectral analysis tasks, including node-level, edge-level, and graph-level classification. It demonstrates robust generalization in both zero-shot and few-shot settings, highlighting its effectiveness in learning from limited data and supporting in-context reasoning. This work establishes a scalable and interpretable foundation for LLM-driven spectral analysis, unifying physical and chemical modalities for scientific applications.

[Arxiv](https://arxiv.org/abs/2506.17761)