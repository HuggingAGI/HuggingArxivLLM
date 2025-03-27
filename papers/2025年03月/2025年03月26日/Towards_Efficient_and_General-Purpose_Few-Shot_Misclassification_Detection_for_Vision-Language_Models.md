# 迈向高效且通用的视觉-语言模型少量样本误分类检测

发布时间：2025年03月26日

`LLM应用` `机器学习` `人工智能`

> Towards Efficient and General-Purpose Few-Shot Misclassification Detection for Vision-Language Models

# 摘要

> 分类器的可靠预测在高安全性和动态变化的场景中至关重要。然而，现代神经网络在错误分类预测中常常表现出过度自信，凸显了置信度估计在检测错误中的重要性。尽管现有方法在小规模数据集上取得了成就，但它们都需要从头开始训练，且缺乏高效、有效的错误分类检测（MisD）方法，这阻碍了其在大规模和动态变化数据集上的实际应用。

本文提出了一种基于视觉语言模型（VLM）的高效通用错误分类检测框架，通过利用文本信息探索VLM的潜力。我们构建了FSMisD，这是一个无需从头训练的小样本提示学习框架，从而提高了调优效率。为了增强错误分类检测能力，我们采用了自适应伪样本生成和一种新的负损失，通过将类别提示与伪特征分离来缓解过度自信问题。

我们进行了全面的提示学习方法实验，并通过领域转移验证了其在各种数据集上的泛化能力。实验结果表明，我们的方法在错误分类检测任务中取得了显著且一致的改进，充分证明了其有效性、效率和通用性。

> Reliable prediction by classifiers is crucial for their deployment in high security and dynamically changing situations. However, modern neural networks often exhibit overconfidence for misclassified predictions, highlighting the need for confidence estimation to detect errors. Despite the achievements obtained by existing methods on small-scale datasets, they all require training from scratch and there are no efficient and effective misclassification detection (MisD) methods, hindering practical application towards large-scale and ever-changing datasets. In this paper, we pave the way to exploit vision language model (VLM) leveraging text information to establish an efficient and general-purpose misclassification detection framework. By harnessing the power of VLM, we construct FSMisD, a Few-Shot prompt learning framework for MisD to refrain from training from scratch and therefore improve tuning efficiency. To enhance misclassification detection ability, we use adaptive pseudo sample generation and a novel negative loss to mitigate the issue of overconfidence by pushing category prompts away from pseudo features. We conduct comprehensive experiments with prompt learning methods and validate the generalization ability across various datasets with domain shift. Significant and consistent improvement demonstrates the effectiveness, efficiency and generalizability of our approach.

[Arxiv](https://arxiv.org/abs/2503.20492)