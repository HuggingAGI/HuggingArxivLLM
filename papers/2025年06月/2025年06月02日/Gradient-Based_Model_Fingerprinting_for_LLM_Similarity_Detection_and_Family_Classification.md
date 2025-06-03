# 基于梯度的模型指纹识别助力LLM相似性检测与家族分类

发布时间：2025年06月02日

`LLM理论` `软件工程` `模型管理`

> Gradient-Based Model Fingerprinting for LLM Similarity Detection and Family Classification

# 摘要

> 大型语言模型（LLMs）已成为现代应用的核心软件组件，但未经授权的模型衍生（如微调、合并和重新分发）带来了严峻的软件工程挑战。与传统软件不同，传统软件在克隆检测和许可证合规性方面已有成熟机制，而LLM生态系统却缺乏有效手段来检测模型血缘关系并强制执行许可协议。这一问题在开源模型创建者（如Meta的LLaMA）要求衍生作品保持命名惯例以示归属时尤为突出，但目前尚无技术手段来验证合规性。

为解决这一问题，我们将LLMs视为需要溯源追踪的软件产物，提出TensorGuard——一个基于梯度的指纹框架，用于LLM相似性检测和家族分类。我们的方法通过分析随机输入扰动在张量层中的梯度响应，提取模型固有的行为特征，这一过程独立于训练数据、水印或特定模型格式。TensorGuard支持广泛采用的safetensors格式，并通过统计分析梯度特征构建高维指纹。这些指纹支持两种功能：通过距离计算直接评估任意模型之间的相似性，以及通过K-Means聚类算法结合领域知识初始化质心，对未知模型进行系统化的家族分类。在包含8个基础模型和50个衍生模型的58个模型（涵盖Llama、Qwen、Gemma、Phi、Mistral五个模型家族）上的实验评估表明，在质心初始化的K-Means聚类下，分类准确率达到94%。

> As Large Language Models (LLMs) become integral software components in modern applications, unauthorized model derivations through fine-tuning, merging, and redistribution have emerged as critical software engineering challenges. Unlike traditional software where clone detection and license compliance are well-established, the LLM ecosystem lacks effective mechanisms to detect model lineage and enforce licensing agreements. This gap is particularly problematic when open-source model creators, such as Meta's LLaMA, require derivative works to maintain naming conventions for attribution, yet no technical means exist to verify compliance.
  To fill this gap, treating LLMs as software artifacts requiring provenance tracking, we present TensorGuard, a gradient-based fingerprinting framework for LLM similarity detection and family classification. Our approach extracts model-intrinsic behavioral signatures by analyzing gradient responses to random input perturbations across tensor layers, operating independently of training data, watermarks, or specific model formats. TensorGuard supports the widely-adopted safetensors format and constructs high-dimensional fingerprints through statistical analysis of gradient features. These fingerprints enable two complementary capabilities: direct pairwise similarity assessment between arbitrary models through distance computation, and systematic family classification of unknown models via the K-Means clustering algorithm with domain-informed centroid initialization using known base models. Experimental evaluation on 58 models comprising 8 base models and 50 derivatives across five model families (Llama, Qwen, Gemma, Phi, Mistral) demonstrates 94% classification accuracy under our centroid-initialized K-Means clustering.

[Arxiv](https://arxiv.org/abs/2506.01631)