# Q-Palette：分数位量化器——实现高效LLM部署的最优位分配

发布时间：2025年09月24日

`LLM应用` `基础理论`

> Q-Palette: Fractional-Bit Quantizers Toward Optimal Bit Allocation for Efficient LLM Deployment

# 摘要

> 我们研究仅权重训练后量化（PTQ）——这种技术无需重新训练，仅用少量甚至无需校准数据就能量化大型语言模型（LLM）的权重。仅权重PTQ对降低LLM推理的内存占用与延迟至关重要，尤其适用于内存受限的小批量推理场景（如边缘设备的个性化推理）。尽管意义重大，但LLM权重分布常因重尾离群值而不规则，给量化带来挑战。近期研究因此提出基于旋转的方法，将权重转换为近高斯分布——这类分布更规则、离群值更少，能有效降低量化误差。本研究首先推导了给定比特预算下高斯化权重的信息论最优比特分配，发现要实现近最优量化性能，关键在于使用接近高斯失真率边界的细粒度分数比特量化器。为将这一理论洞察落地实践，我们提出Q-Palette：这是一套灵活的分数比特量化器工具集，既包含接近最优失真的网格编码量化器，也有针对快速推理优化的简易矢量/标量量化器，且所有量化器均通过优化的CUDA内核在不同位宽下高效实现。此外，我们以Q-Palette为基础组件，提出新型混合方案量化框架，在资源受限情况下联合优化量化器选型与层融合策略。代码开源地址：https://github.com/snu-mllab/Q-Palette。

> We study weight-only post-training quantization (PTQ), which quantizes the weights of a large language model (LLM) without retraining, using little or no calibration data. Weight-only PTQ is crucial for reducing the memory footprint and latency of LLM inference, especially in memory-bound, small-batch inference scenarios, such as personalized inference on edge devices. Despite its importance, irregular weight distributions with heavy-tailed outliers in LLMs complicate quantization, recently motivating rotation-based methods that transform weights into near-Gaussian distributions, which are more regular with fewer outliers, thereby reducing quantization error. In this work, we first derive the information-theoretically optimal bit allocation for Gaussianized weights under given bit budgets, revealing that fine-grained fractional-bit quantizers approaching the Gaussian distortion-rate bound are essential to achieve near-optimal quantization performance. To bridge this theoretical insight and practical implementation, we introduce Q-Palette, a versatile collection of fractional-bit quantizers that range from trellis-coded quantizers offering near-optimal distortion to simpler vector and scalar quantizers optimized for faster inference, all efficiently implemented with optimized CUDA kernels across various bitwidths. Furthermore, leveraging Q-Palette as a foundational component, we propose a novel mixed-scheme quantization framework, jointly optimizing quantizer choices and layer fusion decisions given resource constraints. The code is available at https://github.com/snu-mllab/Q-Palette.

[Arxiv](https://arxiv.org/abs/2509.20214)