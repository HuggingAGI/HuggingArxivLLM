# ChamaleonLLM: 基于推理时聚类的批量感知动态低秩适应

发布时间：2025年02月06日

`LLM应用

理由：这篇论文提出了一个名为ChamaleonLLM的创新框架，旨在通过批次感知聚类和即时生成低秩更新来实现大型语言模型（LLMs）在推理时的自适应。这种方法显著提升了性能，优于传统的微调方法（如LoRA），并且避免了维护多个专家模型的开销。论文的核心是改进LLMs在实际应用中的性能，因此属于LLM应用类别。` `机器学习`

> ChamaleonLLM: Batch-Aware Dynamic Low-Rank Adaptation via Inference-Time Clusters

# 摘要

> # 摘要
最近大型语言模型（LLMs）的突破性进展在各种任务中展现了卓越性能。然而，这些模型通常以固定权重部署，限制了其在推理过程中动态适应现实数据变化的能力。本文提出ChamaleonLLM，一个创新框架，通过批次感知聚类和即时生成低秩更新，实现LLMs在推理时的自适应。与传统微调方法（如LoRA）或依赖固定预学习统一掩码的方法不同，ChamaleonLLM基于聚类批次的聚合统计动态生成解码器权重的自适应修改。通过智能分组相似输入并通过超网络计算上下文感知的低秩更新，ChamaleonLLM显著提升了性能，优于传统LoRA方法，同时避免了维护多个专家模型的开销。实验表明，该方法在语言模型推理中具有高度自适应性。ChamaleonLLM已开源，确保实验可重复性：https://anonymous.4open.science/r/ChamaleonLLM/

> Recent advances in large language models (LLMs) have shown remarkable performance across diverse tasks. However, these models are typically deployed with fixed weights, which limits their ability to adapt dynamically to the variability inherent in real-world data during inference. This paper introduces ChamaleonLLM, a novel framework that enables inference-time adaptation of LLMs by leveraging batch-aware clustering and on-the-fly generation of low-rank updates. Unlike traditional fine-tuning approaches such as Low-Rank Adaptation (LoRA) or methods that rely on a fixed set of pre-learned uniforms (changeable masks), our method dynamically generates adaptive modifications to the decoder weights based on the aggregated statistics of clustered batches. By intelligently grouping similar inputs and computing context-aware low-rank updates via a hyper-network, ChamaleonLLM achieves significant performance gains, outperforming conventional LoRA methods while eliminating the overhead of maintaining multiple expert models. Our experiments highlight the potential of our approach to serve as a versatile and highly adaptive solution for language model inference. ChamaleonLLM is open-sourced to ensure the reproducibility of our experiments: https://anonymous.4open.science/r/ChamaleonLLM/

[Arxiv](https://arxiv.org/abs/2502.04315)