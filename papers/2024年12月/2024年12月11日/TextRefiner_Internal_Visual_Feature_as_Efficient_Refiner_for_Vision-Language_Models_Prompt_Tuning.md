# TextRefiner：内部视觉特征是视觉语言模型提示调优的高效优化器

发布时间：2024年12月11日

`LLM应用` `计算机视觉` `人工智能`

> TextRefiner: Internal Visual Feature as Efficient Refiner for Vision-Language Models Prompt Tuning

# 摘要

> 尽管提示学习在将视觉语言模型（VLMs）应用于下游任务时效率颇高，但现有的方法主要以粗粒度的方式学习提示，即所学到的提示向量在所有类别中通用。如此一来，定制的提示常常难以辨别特定类别的视觉概念，进而阻碍了具有相似或复杂视觉属性类别的迁移性能。近期的一些进展通过借助大型语言模型（LLMs）的外部知识来提供类别描述，从而缓解了这一挑战，不过这会带来显著的推理成本。在本文中，我们推出了 TextRefiner，这是一种即插即用的方法，能够利用 VLMs 的内部知识来优化现有方法的文本提示。具体而言，TextRefiner 构建了一个新颖的本地缓存模块，用于封装从图像分支中的本地标记衍生出的细粒度视觉概念。通过将缓存的视觉描述与文本分支的原始输出进行聚合和对齐，TextRefiner 能够高效地优化和丰富现有方法所学到的提示，且无需依赖任何外部专业知识。比如，它在 11 个基准测试中将 CoOp 的性能从 71.66%提升至 76.94%，超越了为文本提示引入实例特征的 CoCoOp。配备了 TextRefiner 后，PromptKD 实现了顶尖的性能，且推理效率高。我们的代码发布于 https://github.com/xjjxmu/TextRefiner

> Despite the efficiency of prompt learning in transferring vision-language models (VLMs) to downstream tasks, existing methods mainly learn the prompts in a coarse-grained manner where the learned prompt vectors are shared across all categories. Consequently, the tailored prompts often fail to discern class-specific visual concepts, thereby hindering the transferred performance for classes that share similar or complex visual attributes. Recent advances mitigate this challenge by leveraging external knowledge from Large Language Models (LLMs) to furnish class descriptions, yet incurring notable inference costs. In this paper, we introduce TextRefiner, a plug-and-play method to refine the text prompts of existing methods by leveraging the internal knowledge of VLMs. Particularly, TextRefiner builds a novel local cache module to encapsulate fine-grained visual concepts derivedfrom local tokens within the image branch. By aggregating and aligning the cached visual descriptions with the original output of the text branch, TextRefiner can efficiently refine and enrich the learned prompts from existing methods without relying on any external expertise. For example, it improves the performance of CoOp from 71.66 % to 76.94 % on 11 benchmarks, surpassing CoCoOp which introduces instance-wise features for text prompts. Equipped with TextRefiner, PromptKD achieves state-of-the-art performance and is efficient in inference. Our code is relesed at https://github.com/xjjxmu/TextRefiner

[Arxiv](https://arxiv.org/abs/2412.08176)