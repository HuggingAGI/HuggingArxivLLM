# 基于大型语言模型的多维度知识蒸馏

发布时间：2025年01月22日

`LLM应用

理由：这篇论文主要讨论了如何利用多模态大型语言模型（MLLMs）进行多方面知识蒸馏，以提升计算机视觉任务的性能。虽然论文涉及了深度学习、计算机视觉和知识蒸馏等多个领域，但其核心在于利用大型语言模型（LLM）来提取和蒸馏多方面知识，并将其应用于图像分类等任务。因此，这篇论文应归类为LLM应用。` `计算机视觉`

> Multi-aspect Knowledge Distillation with Large Language Model

# 摘要

> # 摘要
深度学习的飞速发展显著提升了计算机视觉任务的性能。传统图像分类方法主要通过调整模型架构或添加特征，并利用交叉熵损失优化类别logits。然而，这些方法过于依赖类别标签，可能难以捕捉类别的多方面特征（如自然位置和形状变化）。为此，我们提出了一种基于多模态大型语言模型（MLLMs）的多方面知识蒸馏方法。具体而言，我们的方法包括：1）向大型语言模型提出与目标知识相关的多方面问题，2）从MLLM中提取相应的logits，3）扩展模型输出维度以蒸馏这些多方面logits。随后，我们对类别logits应用交叉熵损失，对多方面logits应用二元交叉熵损失。通过这一方法，模型不仅能学习视觉特征，还能掌握需要深层理解的抽象和复杂知识。我们主要将方法应用于图像分类，并探索了其在目标检测等任务中的扩展潜力。实验结果表明，我们的方法显著提升了基线模型的性能。此外，我们深入分析了多方面知识蒸馏的效果，证明其能够有效传递多方面知识并提升模型在计算机视觉任务中的表现。本文展示了多方面知识蒸馏的巨大潜力，为计算机视觉及其他领域的未来研究提供了新的方向。

> Recent advancements in deep learning have significantly improved performance on computer vision tasks. Previous image classification methods primarily modify model architectures or add features, and they optimize models using cross-entropy loss on class logits. Since they focus on classifying images with considering class labels, these methods may struggle to learn various \emph{aspects} of classes (e.g., natural positions and shape changes). Rethinking the previous approach from a novel view, we propose a multi-aspect knowledge distillation method using Multimodal Large Language Models (MLLMs). Our approach involves: 1) querying Large Language Model with multi-aspect questions relevant to the knowledge we want to transfer to the model, 2) extracting corresponding logits from MLLM, and 3) expanding the model's output dimensions to distill these multi-aspect logits. We then apply cross-entropy loss to class logits and binary cross-entropy loss to multi-aspect logits. Through our method, the model can learn not only the knowledge about visual aspects but also the abstract and complex aspects that require a deeper understanding. We primarily apply our method to image classification, and to explore the potential for extending our model, we expand it to other tasks, such as object detection. In all experimental results, our method improves the performance of the baselines. Additionally, we analyze the effect of multi-aspect knowledge distillation. These results demonstrate that our method can transfer knowledge about various aspects to the model and the aspect knowledge can enhance model performance in computer vision tasks. This paper demonstrates the great potential of multi-aspect knowledge distillation, and we believe it offers a promising direction for future research in computer vision and beyond.

[Arxiv](https://arxiv.org/abs/2501.13341)