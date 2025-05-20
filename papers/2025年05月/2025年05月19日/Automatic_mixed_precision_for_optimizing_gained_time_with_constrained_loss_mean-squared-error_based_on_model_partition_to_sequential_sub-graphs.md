# 基于模型分割为顺序子图的自动混合精度优化方法，实现受约束均方误差损失下的时间节省。

发布时间：2025年05月19日

`其他` `人工智能`

> Automatic mixed precision for optimizing gained time with constrained loss mean-squared-error based on model partition to sequential sub-graphs

# 摘要

> 量化技术在神经网络压缩中扮演关键角色，通过采用低位宽数据类型降低模型体积和计算复杂度，但过度量化常会影响模型精度。混合精度（MP）通过在不同网络层间动态调整精度，有效平衡了这一矛盾。本研究聚焦于后训练量化（PTQ）中自动选择最优MP配置，以提升推理效率。我们的第一个创新点是一种基于损失函数一阶泰勒展开的敏感性指标，该指标以损失的均方误差（MSE）为基础，通过在小规模校准数据集上进行高精度的前向和反向传播即可快速计算各层的敏感度。该指标具有良好的累加特性，且由于无需权重优化，校准过程几乎不占用额外内存。第二个创新点是一种硬件感知的高效方法，通过将模型划分为顺序子图，利用少量样本即可准确预测MP的时间增益。完成各层敏感度和时间增益的校准后，我们通过整数规划（IP）问题，在确保损失MSE不超过预设阈值的前提下最大化时间增益。同时，我们还考虑了基于乘法和累加（MAC）操作的内存和理论时间增益。在Intel Gaudi 2加速器上的实验证明了该方法在多个大型语言模型（LLMs）上的有效性。


> Quantization is essential for Neural Network (NN) compression, reducing model size and computational demands by using lower bit-width data types, though aggressive reduction often hampers accuracy. Mixed Precision (MP) mitigates this tradeoff by varying the numerical precision across network layers. This study focuses on automatically selecting an optimal MP configuration within Post-Training Quantization (PTQ) for inference. The first key contribution is a novel sensitivity metric derived from a first-order Taylor series expansion of the loss function as a function of quantization errors in weights and activations. This metric, based on the Mean Square Error (MSE) of the loss, is efficiently calculated per layer using high-precision forward and backward passes over a small calibration dataset. The metric is additive across layers, with low calibration memory overhead as weight optimization is unnecessary. The second contribution is an accurate hardware-aware method for predicting MP time gain by modeling it as additive for sequential sub-graphs. An algorithm partitions the model graph into sequential subgraphs, measuring time gain for each configuration using a few samples. After calibrating per-layer sensitivity and time gain, an Integer Programming (IP) problem is formulated to maximize time gain while keeping loss MSE below a set threshold. Memory gain and theoretical time gain based on Multiply and Accumulate (MAC) operations are also considered. Rigorous experiments on the Intel Gaudi 2 accelerator validate the approach on several Large Language Models (LLMs).

[Arxiv](https://arxiv.org/abs/2505.13060)