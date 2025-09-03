# MoPEQ：混合精度量化专家混合体

发布时间：2025年09月02日

`LLM应用` `基础理论`

> MoPEQ: Mixture of Mixed Precision Quantized Experts

# 摘要

> 采用混合专家（MoE）架构的大语言视觉模型由于计算与内存需求高昂，部署时面临巨大挑战。混合精度量化会根据大语言/视觉语言模型（LLM/VLM）各层的敏感性及重要性，为不同层分配不同精度。本研究提出训练后量化算法MoPEQ，可为每个专家分配最优位宽。我们的方法不依赖专家激活频率，而是通过Hessian迹近似分析各专家敏感性，从而平衡精度与模型大小。这种每专家粒度的方法会聚类相似专家，在减少内存需求的同时维持模型性能。在VLMEvalKit基准数据集上，使用最先进的视觉语言模型Deepseek-VL2（-tiny、-small、-base版本）和MolmoE模型进行的实验结果显示：与均匀精度基线方法相比，我们的混合精度量化MoE不仅精度相当，内存占用还大幅减少。我们还开展了全面研究：在层级和模型级为专家分配2、3、4位精度时，通过Hessian迹近似分析专家激活频率与敏感性的影响，从而深入理解视觉语言模型-MoE的混合精度量化。

> Large Language and Vision Models using a Mixture-of-Experts (MoE) architecture pose significant challenges for deployment due to their computational and memory demands. Mixed Precision Quantization assigns different precisions to different layers of an LLM/VLM based on layer sensitivity and importance within the model. In this work, we propose a Post Training Quantization algorithm, MoPEQ, that assigns optimal bit width to each expert. Our method balances accuracy and model size by analyzing each expert's sensitivity using Hessian trace approximation instead of relying on the activation frequency of the expert. This per-expert granularity approach clusters similar experts to maintain model performance while reducing memory requirements. The experimental results on VLMEvalKit benchmark datasets using State-of-the-art VLMs Deepseek-VL2 -tiny, -small, -base, and MolmoE models demonstrate that our mixed precision quantized MoEs achieve competitive accuracy with substantial improvements in memory footprint compared to uniform-precision baseline methods. We perform a comprehensive study to analyze the impact of expert activation frequency and sensitivity using Hessian trace approximation at both layer-wise and model-wide expert precision allocation of 2, 3, and 4 bits to provide a thorough understanding of mixed precision quantization of VLM-MoEs.

[Arxiv](https://arxiv.org/abs/2509.02512)