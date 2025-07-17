# # PoTPTQ：针对大型语言模型的两步幂次方后训练方法

发布时间：2025年07月16日

`LLM理论` `计算资源优化`

> PoTPTQ: A Two-step Power-of-Two Post-training for LLMs

# 摘要

> 大型语言模型 (LLMs) 在自然语言处理 (NLP) 任务中表现卓越，但其高计算资源需求为部署带来了挑战。基于2的幂次量化 (PoT) 是解决这一难题的通用工具。尽管 PoT 量化在 CPU 上通过定点加法实现高效去量化，但在 GPU 上效果不佳，主要归因于去量化过程中符号位的纠缠和顺序位操作。我们提出了一种全新的 LLM 权重 PoT 量化框架，具有两大优势：(i) 在极低精度格式下超越现有最优准确性；(ii) 通过更高效的去量化实现更快推理。为保持量化模型的准确性，我们设计了两步后训练算法：(i) 使用稳健起点初始化量化缩放因子；(ii) 利用最小校准集优化这些缩放因子。我们的 PoT 后训练算法在整数量化领域超越了当前最优水平，尤其在 2 位和 3 位低精度格式下表现突出。该方法加速了浮点推理的去量化步骤，在 NVIDIA V100 上实现 【数学公式】 倍加速，在 NVIDIA RTX 4090 上实现 【数学公式】 倍加速，相较于均匀整数去量化效果显著。


> Large Language Models (LLMs) have demonstrated remarkable performance across various natural language processing (NLP) tasks. However, their deployment is challenging due to the substantial computational resources required. Power-of-two (PoT) quantization is a general tool to counteract this difficulty. Albeit previous works on PoT quantization can be efficiently dequantized on CPUs using fixed-point addition, it showed less effectiveness on GPUs. The reason is entanglement of the sign bit and sequential bit manipulations needed for dequantization. We propose a novel POT quantization framework for LLM weights that (i) outperforms state-of-the-art accuracy in extremely low-precision number formats, and (ii) enables faster inference through more efficient dequantization. To maintain the accuracy of the quantized model, we introduce a two-step post-training algorithm: (i) initialize the quantization scales with a robust starting point, and (ii) refine these scales using a minimal calibration set. The performance of our PoT post-training algorithm surpasses the current state-of-the-art in integer quantization, particularly at low precisions such as 2- and 3-bit formats. Our PoT quantization accelerates the dequantization step required for the floating point inference and leads to $3.67\times$ speed up on a NVIDIA V100, and $1.63\times$ on a NVIDIA RTX 4090, compared to uniform integer dequantization.

[Arxiv](https://arxiv.org/abs/2507.11959)