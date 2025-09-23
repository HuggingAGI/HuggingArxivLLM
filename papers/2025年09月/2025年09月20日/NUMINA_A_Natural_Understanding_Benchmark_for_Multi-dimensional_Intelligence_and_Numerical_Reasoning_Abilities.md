# NUMINA：面向多维智能与数值推理能力的自然理解基准

发布时间：2025年09月20日

`LLM应用` `基础理论`

> NUMINA: A Natural Understanding Benchmark for Multi-dimensional Intelligence and Numerical Reasoning Abilities

# 摘要

> 近年来，二维多模态大型语言模型（MLLMs）的突破性进展大幅提升了视觉-语言任务的表现。然而，受空间推理复杂性的限制，将这些能力拓展到3D环境仍是一项艰巨挑战。尽管如此，现有3D基准测试往往缺乏细粒度的数值推理任务标注，这制约了MLLMs进行精确空间测量和复杂数值推理的能力。为解决这一问题，我们提出了NUMINA——首个专注于提升多模态室内感知理解的多维智能与数值推理能力自然理解基准。NUMINA包含多尺度标注和多样化问答对，这些均由NUMINA-Flow自动生成——这是一个集成了LLM重写与规则化自我验证的自动化标注流水线。我们基于Chat-Scene框架在NUMINA上评估了多种最先进LLMs的性能，发现当前LLMs在多模态数值推理上表现不佳，尤其在精确计算（如距离和体积估计）方面，这凸显了3D模型亟待进一步优化的需求。数据集及源代码可访问https://github.com/fengshun124/NUMINA获取。

> Recent advancements in 2D multimodal large language models (MLLMs) have significantly improved performance in vision-language tasks. However, extending these capabilities to 3D environments remains a distinct challenge due to the complexity of spatial reasoning. Nevertheless, existing 3D benchmarks often lack fine-grained numerical reasoning task annotations, limiting MLLMs' ability to perform precise spatial measurements and complex numerical reasoning. To address this gap, we introduce NUMINA, the first Natural Understanding benchmark for Multi-dimensional Intelligence and Numerical reasoning Abilities to enhance multimodal indoor perceptual understanding. NUMINA features multi-scale annotations and various question-answer pairs, generated using NUMINA-Flow, an automated annotation pipeline that integrates LLM rewriting and rule-based self-verification. We evaluate the performance of various state-of-the-art LLMs on NUMINA following the Chat-Scene framework, demonstrating that current LLMs struggle with multimodal numerical reasoning, particularly in performing precise computations such as distance and volume estimation, highlighting the need for further advancements in 3D models. The dataset and source codes can be obtained from https://github.com/fengshun124/NUMINA.

[Arxiv](https://arxiv.org/abs/2509.16656)