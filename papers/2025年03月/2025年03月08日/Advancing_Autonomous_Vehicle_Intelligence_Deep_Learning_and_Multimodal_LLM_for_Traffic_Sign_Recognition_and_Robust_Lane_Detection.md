# 自动驾驶智能新突破：深度学习与多模态大语言模型助力交通标志识别与鲁棒车道检测

发布时间：2025年03月08日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型在自动驾驶中的应用，特别是在交通标志识别和车道检测方面，展示了LLM在实际场景中的应用潜力。` `自动驾驶` `计算机视觉`

> Advancing Autonomous Vehicle Intelligence: Deep Learning and Multimodal LLM for Traffic Sign Recognition and Robust Lane Detection

# 摘要

> 自动驾驶汽车要在复杂多变的环境中安全行驶，离不开可靠的交通标志识别和强大的车道检测能力。本文提出了一种结合先进深度学习技术和多模态大型语言模型（MLLMs）的综合方案，用于全面的路面感知。在交通标志识别方面，我们对比了ResNet-50、YOLOv8和RT-DETR三种模型，结果表明：ResNet-50表现最佳，达到了99.8%的顶尖水准；YOLOv8紧随其后，准确率达到98.0%；而计算复杂度较高的RT-DETR也实现了96.6%的识别率。在车道检测方面，我们提出了一种基于卷积神经网络的分割方法，并通过多项式曲线拟合进行优化，该方法在理想条件下表现尤为出色。此外，我们开发了一种轻量级、多模态、基于LLM的框架，该框架无需初始预训练，可以直接使用小规模但多样化的小型数据集进行指令微调。该框架能够有效应对各种车道类型、复杂交叉路口和汇流区域，并通过在不利条件下进行推理，显著提升了车道检测的可靠性。尽管在可用训练资源方面存在限制，我们的多模态方法仍展现了强大的推理能力，实现了53.87%的帧整体准确率（FRM）、82.83%的问题整体准确率（QNS）、在良好条件下99.6%的车道检测准确率以及夜间93.0%的车道检测准确率，并在推理因雨导致车道不可见（88.4%）或道路退化（95.6%）方面展现了强大的性能。所提出的综合框架显著提升了自动驾驶汽车的感知可靠性，从而为各种复杂道路场景下的更安全自动驾驶做出了重要贡献。

> Autonomous vehicles (AVs) require reliable traffic sign recognition and robust lane detection capabilities to ensure safe navigation in complex and dynamic environments. This paper introduces an integrated approach combining advanced deep learning techniques and Multimodal Large Language Models (MLLMs) for comprehensive road perception. For traffic sign recognition, we systematically evaluate ResNet-50, YOLOv8, and RT-DETR, achieving state-of-the-art performance of 99.8% with ResNet-50, 98.0% accuracy with YOLOv8, and achieved 96.6% accuracy in RT-DETR despite its higher computational complexity. For lane detection, we propose a CNN-based segmentation method enhanced by polynomial curve fitting, which delivers high accuracy under favorable conditions. Furthermore, we introduce a lightweight, Multimodal, LLM-based framework that directly undergoes instruction tuning using small yet diverse datasets, eliminating the need for initial pretraining. This framework effectively handles various lane types, complex intersections, and merging zones, significantly enhancing lane detection reliability by reasoning under adverse conditions. Despite constraints in available training resources, our multimodal approach demonstrates advanced reasoning capabilities, achieving a Frame Overall Accuracy (FRM) of 53.87%, a Question Overall Accuracy (QNS) of 82.83%, lane detection accuracies of 99.6% in clear conditions and 93.0% at night, and robust performance in reasoning about lane invisibility due to rain (88.4%) or road degradation (95.6%). The proposed comprehensive framework markedly enhances AV perception reliability, thus contributing significantly to safer autonomous driving across diverse and challenging road scenarios.

[Arxiv](https://arxiv.org/abs/2503.06313)