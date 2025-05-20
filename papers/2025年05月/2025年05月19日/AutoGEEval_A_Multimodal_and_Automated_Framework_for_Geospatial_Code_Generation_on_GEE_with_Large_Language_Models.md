# AutoGEEval：一个多模态自动化的地理空间代码生成框架，基于GEE和大型语言模型

发布时间：2025年05月19日

`LLM应用` `地球科学` `地理空间分析`

> AutoGEEval: A Multimodal and Automated Framework for Geospatial Code Generation on GEE with Large Language Models

# 摘要

> 地理空间代码生成已成为人工智能与地球科学分析整合的关键方向。然而，这一领域缺乏标准化的自动评估工具。为此，我们提出了AutoGEEval，这是首个基于大型语言模型（LLMs）的Google Earth Engine（GEE）平台上用于地理空间代码生成任务的多模式、单元级自动化评估框架。基于GEE的Python API，AutoGEEval建立了一个包含1325个测试用例的基准套件（AutoGEEval-Bench），涵盖26种GEE数据类型。该框架集成了问题生成和答案验证组件，实现从函数调用到执行验证的端到端自动化评估流程。AutoGEEval支持从准确性、资源消耗、执行效率和错误类型等多个维度对模型输出进行定量分析。我们评估了18个最先进的LLM，包括通用、推理增强、代码中心和地球科学专用模型，揭示了它们在GEE代码生成中的性能特点和优化潜力。这项工作为地理空间代码生成模型的开发和评估提供了一个统一的协议和基础资源，推动了自然语言到领域特定代码自动翻译的前沿。

> Geospatial code generation is emerging as a key direction in the integration of artificial intelligence and geoscientific analysis. However, there remains a lack of standardized tools for automatic evaluation in this domain. To address this gap, we propose AutoGEEval, the first multimodal, unit-level automated evaluation framework for geospatial code generation tasks on the Google Earth Engine (GEE) platform powered by large language models (LLMs). Built upon the GEE Python API, AutoGEEval establishes a benchmark suite (AutoGEEval-Bench) comprising 1325 test cases that span 26 GEE data types. The framework integrates both question generation and answer verification components to enable an end-to-end automated evaluation pipeline-from function invocation to execution validation. AutoGEEval supports multidimensional quantitative analysis of model outputs in terms of accuracy, resource consumption, execution efficiency, and error types. We evaluate 18 state-of-the-art LLMs-including general-purpose, reasoning-augmented, code-centric, and geoscience-specialized models-revealing their performance characteristics and potential optimization pathways in GEE code generation. This work provides a unified protocol and foundational resource for the development and assessment of geospatial code generation models, advancing the frontier of automated natural language to domain-specific code translation.

[Arxiv](https://arxiv.org/abs/2505.12900)