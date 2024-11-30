# Popeye 是一款集成了视觉与语言处理能力的统一模型，专为在遥感图像中实现多源船舶检测而设计。

发布时间：2024年03月06日

`Agent`

> Popeye: A Unified Visual-Language Model for Multi-Source Ship Detection from Remote Sensing Imagery

# 摘要

> 面对遥感图像中复杂多变的船舶检测难题，一种名为 Popeye 的创新统一视觉-语言模型应运而生，它利用 LLM 强大的泛化能力来解决多源船舶检测问题。首先，我们独创了一种图像-指令-解答的方式，巧妙地将各类船舶检测方法融合至一个通用标注框架内，有效消除了因成像设备和视角差异带来的困扰。随之，Popeye 搭载了一种跨模态图像解读技术，强化了视觉信息与语言描述间的互动理解力，可灵活迁移至任何多源船舶检测场景。为进一步应对不同领域的检测需求，我们设计了一套知识适应机制，让预训练得到的视觉-语言知识成功跨越至 RS 领域。更值得一提的是，Popeye 还无缝集成了 SAM 模块，实现了无额外训练成本的像素级船舶分割。经过在全新构建的指令数据集 MMShip 上的大量实验证明，Popeye 在零样本多源船舶检测方面的性能优于现有专业模型、开放词汇模型以及其他视觉-语言模型。

> Ship detection needs to identify ship locations from remote sensing (RS) scenes. However, due to different imaging payloads, various appearances of ships, and complicated background interference from the bird's eye view, it is difficult to set up a unified paradigm for achieving multi-source ship detection. Therefore, in this article, considering that the large language models (LLMs) emerge the powerful generalization ability, a novel unified visual-language model called Popeye is proposed for multi-source ship detection from RS imagery. First, to bridge the interpretation gap between multi-source images for ship detection, a novel image-instruction-answer way is designed to integrate the various ship detection ways (e.g., horizontal bounding box (HBB), oriented bounding box (OBB)) into a unified labeling paradigm. Then, in view of this, a cross-modal image interpretation method is developed for the proposed Popeye to enhance interactive comprehension ability between visual and language content, which can be easily migrated into any multi-source ship detection task. Subsequently, owing to objective domain differences, a knowledge adaption mechanism is designed to adapt the pre-trained visual-language knowledge from the nature scene into the RS domain for multi-source ship detection. In addition, the segment anything model (SAM) is also seamlessly integrated into the proposed Popeye to achieve pixel-level ship segmentation without additional training costs. Finally, extensive experiments are conducted on the newly constructed instruction dataset named MMShip, and the results indicate that the proposed Popeye outperforms current specialist, open-vocabulary, and other visual-language models for zero-shot multi-source ship detection.

[Arxiv](https://arxiv.org/abs/2403.03790)