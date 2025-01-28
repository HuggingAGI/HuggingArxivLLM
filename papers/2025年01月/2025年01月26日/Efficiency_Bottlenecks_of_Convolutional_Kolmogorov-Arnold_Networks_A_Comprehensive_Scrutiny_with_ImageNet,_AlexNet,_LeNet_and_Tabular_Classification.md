# 卷积Kolmogorov-Arnold网络的效率瓶颈：基于ImageNet、AlexNet、LeNet和表格分类的深度剖析

发布时间：2025年01月26日

`其他

理由：这篇论文主要讨论的是卷积 Kolmogorov-Arnold 网络（CKANs）在图像数据集上的表现，并与标准 CNN 模型进行对比。虽然提到了 Transformer 和注意力机制等与 LLM 相关的技术，但论文的核心内容并不涉及 LLM、Agent 或 RAG 等主题，而是专注于神经网络架构的性能评估。因此，将其分类为“其他”更为合适。` `计算机视觉` `生物科学`

> Efficiency Bottlenecks of Convolutional Kolmogorov-Arnold Networks: A Comprehensive Scrutiny with ImageNet, AlexNet, LeNet and Tabular Classification

# 摘要

> # 摘要
卷积神经网络、Transformer、注意力机制、检索增强生成等算法革新了人工智能领域。最近，Kolmogorov-Arnold 网络的出现挑战了神经网络的基础概念，推动了多层感知器和卷积神经网络的变革。尽管在科学建模中表现不俗，但其效率仍有待提升。本文使用 ImageNet-1k（130 万张图像）、MNIST（6 万张图像）以及生物科学相关的 MoA 表格数据集，训练了卷积 Kolmogorov-Arnold 网络（CKANs），并对比了其在 FLOPS、推理时间、可训练参数数量和训练时间上的表现，评估其准确率、精确率、召回率和 F1 分数，与标准 CNN 模型进行对比。结果表明，CKANs 在小型数据集（如 MoA 和 MNIST）上表现尚可但速度较慢，而在 ImageNet 等大型复杂数据集上则远不及 CNN。本文代码实现见：\href{https://github.com/ashimdahal/Study-of-Convolutional-Kolmogorov-Arnold-networks}{https://github.com/ashimdahal/Study-of-Convolutional-Kolmogorov-Arnold-networks}

> Algorithmic level developments like Convolutional Neural Networks, transformers, attention mechanism, Retrieval Augmented Generation and so on have changed Artificial Intelligence. Recent such development was observed by Kolmogorov-Arnold Networks that suggested to challenge the fundamental concept of a Neural Network, thus change Multilayer Perceptron, and Convolutional Neural Networks. They received a good reception in terms of scientific modeling, yet had some drawbacks in terms of efficiency. In this paper, we train Convolutional Kolmogorov Arnold Networks (CKANs) with the ImageNet-1k dataset with 1.3 million images, MNIST dataset with 60k images and a tabular biological science related MoA dataset and test the promise of CKANs in terms of FLOPS, Inference Time, number of trainable parameters and training time against the accuracy, precision, recall and f-1 score they produce against the standard industry practice on CNN models. We show that the CKANs perform fair yet slower than CNNs in small size dataset like MoA and MNIST but are not nearly comparable as the dataset gets larger and more complex like the ImageNet. The code implementation of this paper can be found on the link: \href{https://github.com/ashimdahal/Study-of-Convolutional-Kolmogorov-Arnold-networks}{https://github.com/ashimdahal/Study-of-Convolutional-Kolmogorov-Arnold-networks}

[Arxiv](https://arxiv.org/abs/2501.15757)