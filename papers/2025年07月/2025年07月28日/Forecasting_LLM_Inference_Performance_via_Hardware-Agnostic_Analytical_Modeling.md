# # 通过硬件无关性分析建模预测LLM推理性能

发布时间：2025年07月28日

`LLM应用` `人工智能` `系统优化`

> Forecasting LLM Inference Performance via Hardware-Agnostic Analytical Modeling

# 摘要

> 大型语言模型（LLMs）正逐步成为个人设备上的本地代理，设备配备CPU、NPU和集成GPU。然而，由于计算和内存需求的动态变化，预测这些异构设备上的推理性能仍具挑战性。现有方法依赖于GPU基准测试或基于机器学习的延迟预测器，这些方法通常硬件特定且缺乏通用性。为此，我们推出了LIFE，一个轻量级、模块化的分析框架，能够以硬件和数据集无关的方式表征LLM推理工作负载。LIFE分析了软件和模型优化（如量化、KV缓存压缩、LoRA适配器、分块预填、不同注意力机制和操作符融合）对TTFT、TPOT和TPS等性能指标的影响。LIFE无需大量数据集基准测试，仅通过硬件规格（如TOPS和内存带宽）即可实现性能预测。我们通过在AMD Ryzen CPUs、NPUs、iGPUs和NVIDIA V100 GPUs上使用Llama2-7B变体进行推理验证了LIFE的预测能力，展示了其在通过系统效率视角预测LLM性能方面的实用性，从而支持在不同硬件平台上高效部署LLM。

> Large language models (LLMs) have been increasingly deployed as local agents on personal devices with CPUs, NPUs and integrated GPUs. However, forecasting inference performance on devices with such heterogeneity remains challenging due to the dynamic compute and memory demands. Existing approaches rely on GPU benchmarking or machine learning-based latency predictors, which are often hardware-specific and lack generalizability. To this end, we introduce LIFE, a lightweight and modular analytical framework that is comprised of modular analytical model of operators, configurable to characterize LLM inference workloads in a hardware and dataset-agnostic manner. LIFE characterizes the influence of software and model optimizations, such as quantization, KV cache compression, LoRA adapters, chunked prefill, different attentions, and operator fusion, on performance metrics such as time-to-first-token (TTFT), time-per-output-token (TPOT) and tokens-per-second (TPS). LIFE enables performance forecasting using only hardware specifications, such as TOPS and memory bandwidth, without requiring extensive dataset benchmarking. We validate LIFE's forecasting with inference on AMD Ryzen CPUs, NPUs, iGPUs and NVIDIA V100 GPUs, with Llama2-7B variants, demonstrating the utility of LIFE in forecasting LLM performance through lens of system efficiency to enable efficient LLM deployment across different hardware platforms.

[Arxiv](https://arxiv.org/abs/2508.00904)