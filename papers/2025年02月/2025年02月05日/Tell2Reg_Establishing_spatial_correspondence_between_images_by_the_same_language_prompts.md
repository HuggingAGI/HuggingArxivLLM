# Tell2Reg: 利用相同语言提示实现图像间的空间对应

发布时间：2025年02月05日

`LLM应用

理由：这篇论文讨论了如何利用预训练的大型多模态模型（如GroundingDINO和SAM）来实现图像配准任务。虽然论文中提到的模型是多模态的，但其核心思想是利用语言提示来指导图像配准，这与大型语言模型（LLM）的应用场景密切相关。因此，这篇论文可以被归类为“LLM应用”。` `图像处理`

> Tell2Reg: Establishing spatial correspondence between images by the same language prompts

# 摘要

> 空间对应关系可以通过分割区域的配对来表示，因此图像配准网络的目标是分割对应区域，而非预测位移场或变换参数。本文展示了如何通过预训练的大型多模态模型（如GroundingDINO和SAM），在两张不同图像上使用相同的语言提示来预测对应区域对。这一方法实现了完全自动化且无需训练的配准算法，可能广泛适用于各类图像配准任务。我们以配准不同受试者的前列腺MR图像为例，展示了实验结果，该任务涉及患者间高度可变的强度和形态。Tell2Reg无需训练，省去了以往配准任务中昂贵且耗时的数据整理和标注工作。该方法在性能上优于无监督学习配准方法，并与弱监督方法相当。此外，定性结果表明，语言语义与空间对应关系之间可能存在潜在关联，包括语言提示区域的空间不变性以及局部与全局对应关系之间语言提示的差异。代码已开源：https://github.com/yanwenCi/Tell2Reg.git。

> Spatial correspondence can be represented by pairs of segmented regions, such that the image registration networks aim to segment corresponding regions rather than predicting displacement fields or transformation parameters. In this work, we show that such a corresponding region pair can be predicted by the same language prompt on two different images using the pre-trained large multimodal models based on GroundingDINO and SAM. This enables a fully automated and training-free registration algorithm, potentially generalisable to a wide range of image registration tasks. In this paper, we present experimental results using one of the challenging tasks, registering inter-subject prostate MR images, which involves both highly variable intensity and morphology between patients. Tell2Reg is training-free, eliminating the need for costly and time-consuming data curation and labelling that was previously required for this registration task. This approach outperforms unsupervised learning-based registration methods tested, and has a performance comparable to weakly-supervised methods. Additional qualitative results are also presented to suggest that, for the first time, there is a potential correlation between language semantics and spatial correspondence, including the spatial invariance in language-prompted regions and the difference in language prompts between the obtained local and global correspondences. Code is available at https://github.com/yanwenCi/Tell2Reg.git.

[Arxiv](https://arxiv.org/abs/2502.03118)