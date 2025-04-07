# 高效可持续的 LLM 推理方案在边缘 AI 中的应用——全面评测量化 LLM 的能效、输出精度与推理速度

发布时间：2025年04月04日

`LLM应用` `边缘计算` `人工智能`

> Sustainable LLM Inference for Edge AI: Evaluating Quantized LLMs for Energy Efficiency, Output Accuracy, and Inference Latency

# 摘要

> 在边缘设备上部署大型语言模型（LLM）面临诸多挑战，包括计算限制、内存限制、推理速度和能耗问题。模型量化作为一种关键技术，通过减小模型大小和降低计算开销，成为实现高效LLM推理的重要手段。本研究对来自Ollama库的28个量化LLM进行了全面分析，这些模型默认采用后训练量化（PTQ）和权重量化技术，并部署在边缘设备（Raspberry Pi 4，4GB RAM）上。我们评估了不同量化级别和任务类型下的能效、推理性能和输出准确性。模型在五个标准化数据集（CommonsenseQA、BIG-Bench Hard、TruthfulQA、GSM8K和HumanEval）上进行基准测试，并使用高精度的硬件级能量测量工具捕捉实际功耗。研究结果揭示了不同量化设置下能效、推理速度和准确性的权衡关系，突出了在资源受限环境中优化LLM部署的配置方案。通过将硬件级能效分析与LLM基准测试相结合，本研究为可持续AI提供了实用见解，填补了现有研究中关于能耗感知型LLM部署的关键空白。

> Deploying Large Language Models (LLMs) on edge devices presents significant challenges due to computational constraints, memory limitations, inference speed, and energy consumption. Model quantization has emerged as a key technique to enable efficient LLM inference by reducing model size and computational overhead. In this study, we conduct a comprehensive analysis of 28 quantized LLMs from the Ollama library, which applies by default Post-Training Quantization (PTQ) and weight-only quantization techniques, deployed on an edge device (Raspberry Pi 4 with 4GB RAM). We evaluate energy efficiency, inference performance, and output accuracy across multiple quantization levels and task types. Models are benchmarked on five standardized datasets (CommonsenseQA, BIG-Bench Hard, TruthfulQA, GSM8K, and HumanEval), and we employ a high-resolution, hardware-based energy measurement tool to capture real-world power consumption. Our findings reveal the trade-offs between energy efficiency, inference speed, and accuracy in different quantization settings, highlighting configurations that optimize LLM deployment for resource-constrained environments. By integrating hardware-level energy profiling with LLM benchmarking, this study provides actionable insights for sustainable AI, bridging a critical gap in existing research on energy-aware LLM deployment.

[Arxiv](https://arxiv.org/abs/2504.03360)