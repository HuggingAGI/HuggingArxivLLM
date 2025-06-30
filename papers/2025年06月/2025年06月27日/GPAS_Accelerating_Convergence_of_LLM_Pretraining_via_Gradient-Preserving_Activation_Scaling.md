# GPAS: 利用梯度保持激活缩放加速LLM预训练的收敛过程

发布时间：2025年06月27日

`LLM理论` `模型训练`

> GPAS: Accelerating Convergence of LLM Pretraining via Gradient-Preserving Activation Scaling

# 摘要

> 现代大型语言模型，如LLaMA、Qwen和DeepSeek系列，主要采用Pre-LN Transformer架构。虽然Pre-LN在预训练中表现稳定且可扩展至大模型，但其各层激活方差呈指数级增长，导致残差路径主导子层输出，限制了深层学习能力。为解决此问题，我们提出Gradient-Preserving Activation Scaling（GPAS），一种可与现有方法结合使用的简单技术。GPAS通过在保持梯度不变的同时缩小中间激活值，保留了激活中的信息，避免了梯度消失问题。实验结果表明，GPAS在从71M到1B参数规模的模型中均实现了性能提升。除了增强Pre-LN Transformer，GPAS还在Sandwich-LN和DeepNorm等其他架构中展现出潜力，证明了其多样性和在各种设置中提升训练动态的潜力。

> Modern Large Language Models, such as the LLaMA, Qwen and DeepSeek series, predominantly adopt the Pre-LayerNorm (Pre-LN) Transformer architecture. While being stable during pretraining and scalable to large model sizes, Pre-LN suffers from an exponential growth in activation variance across layers, causing the residual path to dominate over sub-layer outputs and limiting the learning capacity of deeper layers. To mitigate this issue, we propose Gradient-Preserving Activation Scaling (GPAS), a simple technique that can be used in combination with existing approaches. GPAS works by scaling down the intermediate activations while keeping their gradients unchanged. This leaves information in the activations intact, and avoids the gradient vanishing problem associated with gradient downscaling. Extensive experiments across various model sizes from 71M to 1B show that GPAS achieves consistent performance gains. Beyond enhancing Pre-LN Transformers, GPAS also shows promise in improving alternative architectures such as Sandwich-LN and DeepNorm, demonstrating its versatility and potential for improving training dynamics in a wide range of settings.

[Arxiv](https://arxiv.org/abs/2506.22049)