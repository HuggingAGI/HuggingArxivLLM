# Radio方法：大型语言模型压缩中的率失真优化

发布时间：2025年05月05日

`LLM理论` `模型压缩`

> Radio: Rate-Distortion Optimization for Large Language Model Compression

# 摘要

> 近年来，大型语言模型（LLMs）的压缩已成为关键问题，它不仅能在资源受限设备上促进LLM部署，还能降低计算成本并减少大规模AI基础设施对环境的影响。我们从信息率失真理论的角度为LLM量化奠定了基础，并提出了一种基于简单率失真优化的量化技术。该技术可扩展至包含数百亿个权重参数的模型，并允许用户在训练后将其压缩至指定的模型大小或准确度。

> In recent years, the compression of large language models (LLMs) has emerged as a key problem in facilitating LLM deployment on resource-limited devices, reducing compute costs, and mitigating the environmental footprint due to large-scale AI infrastructure. Here, we establish the foundations of LLM quantization from a rate-distortion theory perspective and propose a quantization technique based on simple rate-distortion optimization. Our technique scales to models containing hundreds of billions of weight parameters and offers users the flexibility to compress models, post-training, to a model size or accuracy specified by the user.

[Arxiv](https://arxiv.org/abs/2505.03031)