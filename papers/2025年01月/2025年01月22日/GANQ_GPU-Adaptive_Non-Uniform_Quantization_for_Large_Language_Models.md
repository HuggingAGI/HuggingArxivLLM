# GANQ: 大型语言模型的GPU自适应非均匀量化

发布时间：2025年01月22日

`LLM应用

**理由**：这篇论文主要讨论了如何通过量化技术来优化大型语言模型（LLMs）的部署，特别是针对内存占用和推理效率的改进。这属于LLM在实际应用中的优化问题，因此归类为LLM应用。` `硬件优化`

> GANQ: GPU-Adaptive Non-Uniform Quantization for Large Language Models

# 摘要

> 大型语言模型（LLMs）因资源需求巨大，部署面临显著挑战。尽管低位量化权重能减少内存占用并提升推理效率，但现有硬件对混合精度通用矩阵乘法（mpGEMM）缺乏原生支持，导致反量化实现效率低下。此外，均匀量化方法常无法充分捕捉权重分布，导致性能下降。我们提出GANQ（GPU自适应非均匀量化），这是一个针对硬件高效查找表mpGEMM优化的分层后训练非均匀量化框架。GANQ通过无需训练的GPU自适应优化算法，有效降低分层量化误差，实现卓越量化性能。大量实验表明，GANQ在3位和4位量化中，相比最先进方法，显著缩小了与FP16基线的困惑度差距。此外，在单个NVIDIA RTX 4090 GPU上部署时，GANQ量化模型比基线加速高达2.57$	imes$，显著提升了LLM部署的内存和推理效率。

> Large Language Models (LLMs) face significant deployment challenges due to their substantial resource requirements. While low-bit quantized weights can reduce memory usage and improve inference efficiency, current hardware lacks native support for mixed-precision General Matrix Multiplication (mpGEMM), resulting in inefficient dequantization-based implementations. Moreover, uniform quantization methods often fail to capture weight distributions adequately, leading to performance degradation. We propose GANQ (GPU-Adaptive Non-Uniform Quantization), a layer-wise post-training non-uniform quantization framework optimized for hardware-efficient lookup table-based mpGEMM. GANQ achieves superior quantization performance by utilizing a training-free, GPU-adaptive optimization algorithm to efficiently reduce layer-wise quantization errors. Extensive experiments demonstrate GANQ's ability to reduce the perplexity gap from the FP16 baseline compared to state-of-the-art methods for both 3-bit and 4-bit quantization. Furthermore, when deployed on a single NVIDIA RTX 4090 GPU, GANQ's quantized models achieve up to 2.57$\times$ speedup over the baseline, advancing memory and inference efficiency in LLM deployment.

[Arxiv](https://arxiv.org/abs/2501.12956)