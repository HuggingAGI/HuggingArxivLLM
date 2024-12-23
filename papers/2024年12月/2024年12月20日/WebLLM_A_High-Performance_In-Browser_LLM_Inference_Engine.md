# WebLLM：一款高性能的浏览器内 LLM 推理引擎

发布时间：2024年12月20日

`LLM应用` `浏览器`

> WebLLM: A High-Performance In-Browser LLM Inference Engine

# 摘要

> 大型语言模型（LLMs）的发展展现出了非凡的能力。尽管部署这类模型通常需要服务器级别的 GPU 和基于云的推理，然而近期较小的开源模型的出现以及消费设备性能的不断提升，使得在设备端进行部署成为可能。网络浏览器作为设备端部署的平台，具有普遍可访问性，能提供自然的智能环境，还能方便地将不同设备供应商的后端差异进行抽象。为了把握这一机遇，我们推出了 WebLLM，这是一个开源的 JavaScript 框架，能够在网络浏览器内实现高性能的 LLM 推理。WebLLM 为无缝融入网络应用提供了 OpenAI 式的 API，并借助 WebGPU 实现高效的本地 GPU 加速，利用 WebAssembly 进行高效的 CPU 计算。依靠机器学习编译器 MLC-LLM 和 Apache TVM，WebLLM 运用优化的 WebGPU 内核，弥补了高性能 WebGPU 内核库的缺失。评估显示，WebLLM 在同一设备上能保留高达 80%的原生性能，且还有进一步缩小差距的余地。WebLLM 为网络浏览器中普遍可用、隐私保护、个性化和本地驱动的 LLM 应用开辟了道路。代码可在：https://github.com/mlc-ai/web-llm 获取。

> Advancements in large language models (LLMs) have unlocked remarkable capabilities. While deploying these models typically requires server-grade GPUs and cloud-based inference, the recent emergence of smaller open-source models and increasingly powerful consumer devices have made on-device deployment practical. The web browser as a platform for on-device deployment is universally accessible, provides a natural agentic environment, and conveniently abstracts out the different backends from diverse device vendors. To address this opportunity, we introduce WebLLM, an open-source JavaScript framework that enables high-performance LLM inference entirely within web browsers. WebLLM provides an OpenAI-style API for seamless integration into web applications, and leverages WebGPU for efficient local GPU acceleration and WebAssembly for performant CPU computation. With machine learning compilers MLC-LLM and Apache TVM, WebLLM leverages optimized WebGPU kernels, overcoming the absence of performant WebGPU kernel libraries. Evaluations show that WebLLM can retain up to 80% native performance on the same device, with room to further close the gap. WebLLM paves the way for universally accessible, privacy-preserving, personalized, and locally powered LLM applications in web browsers. The code is available at: https://github.com/mlc-ai/web-llm.

[Arxiv](https://arxiv.org/abs/2412.15803)