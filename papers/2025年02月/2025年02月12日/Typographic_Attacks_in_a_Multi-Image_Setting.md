# 多图像场景下的排版攻击

发布时间：2025年02月12日

`LLM应用` `计算机视觉` `模型安全`

> Typographic Attacks in a Multi-Image Setting

# 摘要

> 大型视觉语言模型（LVLMs）易受排版攻击影响，这类攻击通过在图像上添加攻击文本导致误分类。本文提出了一种多图像攻击场景，扩展了现有研究主要聚焦于单图像攻击的局限。我们特别关注无需重复攻击查询的图像集合攻击。这种非重复攻击更具隐蔽性，因其更可能规避看门人机制。我们针对多图像场景提出了两种攻击策略，分别基于目标图像的难度、攻击文本的强度以及文本与图像的相似性。我们的文本-图像相似度方法在ImageNet上使用CLIP模型时，相较于随机非特异性攻击方法，将攻击成功率提升了21%，同时在多图像场景中保持了隐蔽性。额外实验表明，使用CLIP计算的文本-图像相似度在攻击InstructBLIP时同样有效，展示了良好的可迁移性。

> Large Vision-Language Models (LVLMs) are susceptible to typographic attacks, which are misclassifications caused by an attack text that is added to an image. In this paper, we introduce a multi-image setting for studying typographic attacks, broadening the current emphasis of the literature on attacking individual images. Specifically, our focus is on attacking image sets without repeating the attack query. Such non-repeating attacks are stealthier, as they are more likely to evade a gatekeeper than attacks that repeat the same attack text. We introduce two attack strategies for the multi-image setting, leveraging the difficulty of the target image, the strength of the attack text, and text-image similarity. Our text-image similarity approach improves attack success rates by 21% over random, non-specific methods on the CLIP model using ImageNet while maintaining stealth in a multi-image scenario. An additional experiment demonstrates transferability, i.e., text-image similarity calculated using CLIP transfers when attacking InstructBLIP.

[Arxiv](https://arxiv.org/abs/2502.08193)