# 如何从您的模型中获取一个解释

发布时间：2024年12月06日

`其他` `生物识别`

> How to Squeeze An Explanation Out of Your Model

# 摘要

> 如今，深度学习模型因执行各类任务时的可靠性而被广泛运用。但它们通常不给出决策背后的推理，这是个明显的短板，在生物识别、安全和医疗保健等更为敏感的领域尤甚。提供可解释性最常用的办法是基于模型梯度反向传播，在图像上生成感兴趣区域的视觉注意力热图。虽说这办法可行，可当下的方法是针对图像设定和默认/标准的深度学习模型的，意味着要在视频/多模态设定和自定义架构上运行，就得做大幅调整。本文提出了一种与模型无关的可解释性方法，基于对挤压和激励（SE）模块的创新运用来创建视觉注意力热图。在任何模型的分类层前加入一个 SE 模块，我们就能通过 SE 向量操作获取最具影响力的特征，这是 SE 模块的关键组成部分之一。我们的结果显示，这种新的基于 SE 的可解释性能够应用于图像和视频/多模态设定中的各种模型，比如用 CelebA 进行面部特征生物识别，以及用主动说话者检测数据集进行行为生物识别。另外，我们的方案不会影响模型在原始任务上的性能，在最先进的对象数据集中与当前的可解释性方法相比也有竞争力，凸显了其在生物识别语境之外的不同数据中的稳健性。

> Deep learning models are widely used nowadays for their reliability in performing various tasks. However, they do not typically provide the reasoning behind their decision, which is a significant drawback, particularly for more sensitive areas such as biometrics, security and healthcare. The most commonly used approaches to provide interpretability create visual attention heatmaps of regions of interest on an image based on models gradient backpropagation. Although this is a viable approach, current methods are targeted toward image settings and default/standard deep learning models, meaning that they require significant adaptations to work on video/multi-modal settings and custom architectures. This paper proposes an approach for interpretability that is model-agnostic, based on a novel use of the Squeeze and Excitation (SE) block that creates visual attention heatmaps. By including an SE block prior to the classification layer of any model, we are able to retrieve the most influential features via SE vector manipulation, one of the key components of the SE block. Our results show that this new SE-based interpretability can be applied to various models in image and video/multi-modal settings, namely biometrics of facial features with CelebA and behavioral biometrics using Active Speaker Detection datasets. Furthermore, our proposal does not compromise model performance toward the original task, and has competitive results with current interpretability approaches in state-of-the-art object datasets, highlighting its robustness to perform in varying data aside from the biometric context.

[Arxiv](https://arxiv.org/abs/2412.05134)