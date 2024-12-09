# BEExformer：一种借助具有多个早期出口的二值化来实现快速推理的 Transformer 架构

发布时间：2024年12月06日

`LLM应用` `计算机架构`

> BEExformer: A Fast Inferencing Transformer Architecture via Binarization with Multiple Early Exits

# 摘要

> 基于转换器的大型语言模型（LLMs）在各类应用中斩获前沿成果。然而，其庞大的规模和处理需求致使在资源有限的设备上部署变得极为困难。在众多效率考量中，模型二值化和早期退出（EE）是常见的有效手段。但二值化可能因精度降低影响梯度估算和参数更新，从而导致性能损失。另外，当下的早期退出机制仍处于研究的初始阶段。为改进这些问题，我们提出了二值化早期退出转换器（BEExformer），这是首个将早期退出与二值化相结合用于文本推理的选择性学习转换器架构。它通过对脉冲函数的可微二阶近似来优化二值化过程，从而能够计算权重的符号和大小的梯度。与基于绝对阈值的 EE 不同，所提出的 EE 机制取决于中间转换器块之间熵的分数降低，并通过软路由损失估算。二值化使模型规模缩小 18.44 倍，早期退出在推理时将 FLOPs 减少 54.85%，甚至通过解决深度网络固有的“过度思考”问题将准确率提高 5.98%。此外，所提出的 BEExformer 简化了训练，无需从全精度 LLM 进行知识蒸馏。在 GLUE 数据集上的广泛评估以及与 SOTA 成果的对比，展现了其帕累托最优的性能 - 效率平衡。

> Large Language Models (LLMs) based on transformers achieve cutting-edge results on a variety of applications. However, their enormous size and processing requirements make deployment on devices with constrained resources extremely difficult. Among various efficiency considerations, model binarization and Early Exit (EE) are common effective solutions. However, binarization may lead to performance loss due to reduced precision affecting gradient estimation and parameter updates. Besides, the present early-exit mechanisms are still in the nascent stages of research. To ameliorate these issues, we propose Binarized Early Exit Transformer (BEExformer), the first-ever selective learning transformer architecture to combine early exit with binarization for textual inference. It improves the binarization process through a differentiable second-order approximation to the impulse function. This enables gradient computation concerning both the sign as well as the magnitude of the weights. In contrast to absolute threshold-based EE, the proposed EE mechanism hinges on fractional reduction in entropy among intermediate transformer blocks with soft-routing loss estimation. While binarization results in 18.44 times reduction in model size, early exit reduces the FLOPs during inference by 54.85% and even improves accuracy by 5.98% through resolving the "overthinking" problem inherent in deep networks. Moreover, the proposed BEExformer simplifies training by not requiring knowledge distillation from a full-precision LLM. Extensive evaluation on the GLUE dataset and comparison with the SOTA works showcase its pareto-optimal performance-efficiency trade-off.

[Arxiv](https://arxiv.org/abs/2412.05225)