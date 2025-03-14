# 把握机器学习系统的语义流动

发布时间：2025年03月13日

`LLM理论` `机器学习` `软件工程`

> Capturing Semantic Flow of ML-based Systems

# 摘要

> 基于机器学习的系统集成了深度神经网络 (DNN) 或大型语言模型 (LLM) 等组件，能够实现高性能计算机视觉、自然语言处理和代码生成等功能。然而，传统的动态分析方法如测试难以洞察这些系统的内部行为，现有分析通常仅关注外部可观察的内容，例如输入相似性或类别标签的变化。我们提出语义流这一概念，旨在捕捉基于机器学习系统的内部行为，并为传统动态分析技术的适应提供平台。语义流结合了控制流的概念与基于机器学习系统执行中的内部状态，例如 DNN 中特定层的激活值，或 LLM 代理在特定推理步骤的响应嵌入。通过语义流图表示的最终结果，能够捕获传统基于机器学习系统的控制流中未明确表示的内部决策。本文提出语义流的概念，通过 DNN 和 LLM 代理的两个示例进行说明，并概述其特性及其如何被用于适应现有动态分析技术以应用于基于机器学习的软件系统。

> ML-based systems are software systems that incorporates machine learning components such as Deep Neural Networks (DNNs) or Large Language Models (LLMs). While such systems enable advanced features such as high performance computer vision, natural language processing, and code generation, their internal behaviour remain largely opaque to traditional dynamic analysis such as testing: existing analysis typically concern only what is observable from the outside, such as input similarity or class label changes. We propose semantic flow, a concept designed to capture the internal behaviour of ML-based system and to provide a platform for traditional dynamic analysis techniques to be adapted to. Semantic flow combines the idea of control flow with internal states taken from executions of ML-based systems, such as activation values of a specific layer in a DNN, or embeddings of LLM responses at a specific inference step of LLM agents. The resulting representation, summarised as semantic flow graphs, can capture internal decisions that are not explicitly represented in the traditional control flow of ML-based systems. We propose the idea of semantic flow, introduce two examples using a DNN and an LLM agent, and finally sketch its properties and how it can be used to adapt existing dynamic analysis techniques for use in ML-based software systems.

[Arxiv](https://arxiv.org/abs/2503.10310)