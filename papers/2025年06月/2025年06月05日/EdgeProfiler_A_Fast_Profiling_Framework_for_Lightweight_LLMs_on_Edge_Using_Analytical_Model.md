# EdgeProfiler：基于分析模型的边缘设备轻量级大语言模型高效分析框架。

发布时间：2025年06月05日

`LLM应用` `边缘计算` `嵌入式系统`

> EdgeProfiler: A Fast Profiling Framework for Lightweight LLMs on Edge Using Analytical Model

# 摘要

> 本研究提出了一种名为EdgeProfiler的快速性能分析框架，专为在边缘系统中评估轻量级大型语言模型（LLMs）而设计。尽管LLMs在自然语言理解和生成方面表现出色，但其对计算、内存和功耗的高需求通常使其局限于云计算环境。EdgeProfiler通过提供一种系统化的评估方法，能够在资源受限的边缘环境中评估LLM的性能。该框架采用激进的量化技术和严格的内存限制，对包括TinyLLaMA、Gemma3.1B、Llama3.2-1B和DeepSeek-r1-1.5B在内的轻量化LLMs进行性能分析。通过分析建模，我们能够估算推理延迟、浮点运算量和能耗。性能分析结果显示，4位量化技术可将模型内存占用减少约60-70%，同时将精度保持在全精度基准的2-5%以内。与FP16基准相比，推理速度在各类边缘设备上提升了2-3倍。功耗建模表明，INT4配置可将能耗降低35-50%，从而实现在Raspberry Pi 4/5和Jetson Orin Nano Super等硬件上的实际部署。我们的研究结果强调了针对边缘环境中轻量化LLMs进行高效性能分析的重要性，能够在保证精度的同时，实现能源效率和计算可行性的平衡。

> This paper introduces EdgeProfiler, a fast profiling framework designed for evaluating lightweight Large Language Models (LLMs) on edge systems. While LLMs offer remarkable capabilities in natural language understanding and generation, their high computational, memory, and power requirements often confine them to cloud environments. EdgeProfiler addresses these challenges by providing a systematic methodology for assessing LLM performance in resource-constrained edge settings. The framework profiles compact LLMs, including TinyLLaMA, Gemma3.1B, Llama3.2-1B, and DeepSeek-r1-1.5B, using aggressive quantization techniques and strict memory constraints. Analytical modeling is used to estimate latency, FLOPs, and energy consumption. The profiling reveals that 4-bit quantization reduces model memory usage by approximately 60-70%, while maintaining accuracy within 2-5% of full-precision baselines. Inference speeds are observed to improve by 2-3x compared to FP16 baselines across various edge devices. Power modeling estimates a 35-50% reduction in energy consumption for INT4 configurations, enabling practical deployment on hardware such as Raspberry Pi 4/5 and Jetson Orin Nano Super. Our findings emphasize the importance of efficient profiling tailored to lightweight LLMs in edge environments, balancing accuracy, energy efficiency, and computational feasibility.

[Arxiv](https://arxiv.org/abs/2506.09061)