# AmCLR：跨模态表示的统一增强式学习

发布时间：2024年12月10日

`LLM应用` `计算机视觉` `多模态学习`

> AmCLR: Unified Augmented Learning for Cross-Modal Representations

# 摘要

> 对比学习已成为表示学习的关键架构，助力了像 SimCLR 和 CLIP 这样的单模态及双模态应用的发展。为应对大批次依赖和双模态等基本局限，诸如 SogCLR 之类的方法借助随机优化来达成全局对比目标。受 SogCLR 效率和适应性的启发，我们推出了专为双模态视觉语言模型定制的 AmCLR 和 xAmCLR 目标函数，进一步强化对比学习的稳健性。AmCLR 融合了多种增强手段，包括文本改写和图像变换，强化对比表示的对齐，将批次大小限制在几百个样本，不像 CLIP 需 32768 的批次大小才能得出合理结果。xAmCLR 进一步拓展这一模式，纳入原始和增强模态间的模态内对齐，以实现更丰富的特征学习。这些进展造就了更具弹性和通用性的对比学习流程，旨在突破缩放和增强多样性方面的瓶颈。鉴于我们在现有的 SogCLR 之上构建了框架，能够以更少的计算资源展现出更优的表示质量，为可扩展且强大的多模态学习奠定基础。

> Contrastive learning has emerged as a pivotal framework for representation learning, underpinning advances in both unimodal and bimodal applications like SimCLR and CLIP. To address fundamental limitations like large batch size dependency and bimodality, methods such as SogCLR leverage stochastic optimization for the global contrastive objective. Inspired by SogCLR's efficiency and adaptability, we introduce AmCLR and xAmCLR objective functions tailored for bimodal vision-language models to further enhance the robustness of contrastive learning. AmCLR integrates diverse augmentations, including text paraphrasing and image transformations, to reinforce the alignment of contrastive representations, keeping batch size limited to a few hundred samples unlike CLIP which needs batch size of 32,768 to produce reasonable results. xAmCLR further extends this paradigm by incorporating intra-modal alignments between original and augmented modalities for richer feature learning. These advancements yield a more resilient and generalizable contrastive learning process, aimed at overcoming bottlenecks in scaling and augmentative diversity. Since we have built our framework on the existing SogCLR, we are able to demonstrate improved representation quality with fewer computational resources, establishing a foundation for scalable and robust multi-modal learning.

[Arxiv](https://arxiv.org/abs/2412.07979)