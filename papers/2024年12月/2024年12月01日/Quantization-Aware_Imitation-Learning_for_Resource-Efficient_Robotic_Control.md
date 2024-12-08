# 用于资源高效机器人控制的量化感知模仿学习

发布时间：2024年12月01日

`其他` `机器人` `自动驾驶`

> Quantization-Aware Imitation-Learning for Resource-Efficient Robotic Control

# 摘要

> 以深度神经网络（DNN）为基础的策略模型，像视觉语言动作（VLA）模型，在通过解读多模态数据实现跨应用的复杂决策自动化方面具有变革意义。然而，此类模型的规模扩展大幅增加了计算成本，这给诸如机器人操控和自动驾驶等需要快速、精准响应的领域带来了难题。为满足在资源有限的硬件上进行部署的需求，我们针对基于 IL 的策略模型提出了一个新的量化框架，该框架通过微调参数来增强训练期间对低位精度误差的稳健性，从而在受限条件下维持效率和可靠性。我们在真实边缘 GPU 上针对具有代表性的机器人操控进行 4 位权重量化的评估显示，我们的框架在保证准确性的同时，实现了高达 2.5 倍的加速和 2.5 倍的节能。对于 4 位权重和激活量化的自动驾驶模型，该框架在低端 GPU 上实现了高达 3.7 倍的加速和 3.1 倍的节能。这些成果凸显了在资源受限设备上部署基于 IL 的策略模型的实际潜力。

> Deep neural network (DNN)-based policy models like vision-language-action (VLA) models are transformative in automating complex decision-making across applications by interpreting multi-modal data. However, scaling these models greatly increases computational costs, which presents challenges in fields like robot manipulation and autonomous driving that require quick, accurate responses. To address the need for deployment on resource-limited hardware, we propose a new quantization framework for IL-based policy models that fine-tunes parameters to enhance robustness against low-bit precision errors during training, thereby maintaining efficiency and reliability under constrained conditions. Our evaluations with representative robot manipulation for 4-bit weight-quantization on a real edge GPU demonstrate that our framework achieves up to 2.5x speedup and 2.5x energy savings while preserving accuracy. For 4-bit weight and activation quantized self-driving models, the framework achieves up to 3.7x speedup and 3.1x energy saving on a low-end GPU. These results highlight the practical potential of deploying IL-based policy models on resource-constrained devices.

[Arxiv](https://arxiv.org/abs/2412.01034)