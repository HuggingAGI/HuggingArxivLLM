# SmartHome-Bench：基于多模态大型语言模型的智能家居视频异常检测综合性基准测试

发布时间：2025年06月15日

`LLM应用` `计算机视觉` `智能家居`

> SmartHome-Bench: A Comprehensive Benchmark for Video Anomaly Detection in Smart Homes Using Multi-Modal Large Language Models

# 摘要

> 视频异常检测（VAD）在识别不同环境中的异常事件、提升安全性和保障方面发挥着关键作用。然而，现有的VAD基准主要针对通用场景设计，忽视了智能家居应用的独特需求。为解决这一问题，我们推出了SmartHome-Bench，这是首个专为智能家居场景设计的全面VAD基准，重点关注多模态大语言模型（MLLMs）的能力。该基准包含1203段由智能家居摄像头录制的视频，根据包含野生动物、老人看护和婴儿监护等七类的新型异常分类法进行整理。每段视频均经过细致标注，包含异常标签、详细描述及推理信息。我们进一步探索了MLLMs在VAD中的适应方法，评估了多种提示技术下的先进闭源和开源模型。结果显示，现有模型在准确检测视频异常方面存在显著局限。针对这些限制，我们提出了一种新的LLM链框架——基于分类法的反思型LLM链（TRLC），实现了检测准确率11.62%的显著提升。该基准数据集和代码现已公开，可访问https://github.com/Xinyi-0724/SmartHome-Bench-LLM获取。

> Video anomaly detection (VAD) is essential for enhancing safety and security by identifying unusual events across different environments. Existing VAD benchmarks, however, are primarily designed for general-purpose scenarios, neglecting the specific characteristics of smart home applications. To bridge this gap, we introduce SmartHome-Bench, the first comprehensive benchmark specially designed for evaluating VAD in smart home scenarios, focusing on the capabilities of multi-modal large language models (MLLMs). Our newly proposed benchmark consists of 1,203 videos recorded by smart home cameras, organized according to a novel anomaly taxonomy that includes seven categories, such as Wildlife, Senior Care, and Baby Monitoring. Each video is meticulously annotated with anomaly tags, detailed descriptions, and reasoning. We further investigate adaptation methods for MLLMs in VAD, assessing state-of-the-art closed-source and open-source models with various prompting techniques. Results reveal significant limitations in the current models' ability to detect video anomalies accurately. To address these limitations, we introduce the Taxonomy-Driven Reflective LLM Chain (TRLC), a new LLM chaining framework that achieves a notable 11.62% improvement in detection accuracy. The benchmark dataset and code are publicly available at https://github.com/Xinyi-0724/SmartHome-Bench-LLM.

[Arxiv](https://arxiv.org/abs/2506.12992)