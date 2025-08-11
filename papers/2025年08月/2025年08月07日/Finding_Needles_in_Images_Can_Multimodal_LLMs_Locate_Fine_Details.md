# # 在图像中寻找细针：多模态LLM能否精准定位细节？
# Finding Needles in Images: Can Multimodal LLMs Locate Fine Details?

发布时间：2025年08月07日

`LLM应用` `文档处理` `信息提取`

> Finding Needles in Images: Can Multimodal LLMs Locate Fine Details?

# 摘要

> 多模态大型语言模型（MLLMs）在文档理解任务中表现优异，但在处理复杂文档中的细粒度细节方面仍有待深入研究。例如，在菜单中查找特定营养信息，或在长篇文章中识别免责声明，这些任务需要在整体叙述中细致关注小而重要的细节，类似于图像中的“找针”任务（NiM）。为填补这一研究空白，我们推出了NiM，一个精心策划的基准测试，涵盖报纸、菜单和讲座图像等多样化的现实文档，专为评估MLLMs在这些复杂任务中的能力而设计。在此基础上，我们进一步提出了Spot-IT，一种简单而有效的方法，通过智能补丁选择和高斯注意力机制提升MLLMs的能力，灵感源自人类在文档搜索时的缩放与聚焦行为。我们的实验结果不仅揭示了当前MLLMs在细粒度文档理解任务中的能力与局限，更证明了Spot-IT方法的显著优势，尤其在需要从复杂布局中精准提取细节的场景中表现突出。

> While Multi-modal Large Language Models (MLLMs) have shown impressive capabilities in document understanding tasks, their ability to locate and reason about fine-grained details within complex documents remains understudied. Consider searching a restaurant menu for a specific nutritional detail or identifying a disclaimer in a lengthy newspaper article tasks that demand careful attention to small but significant details within a broader narrative, akin to Finding Needles in Images (NiM). To address this gap, we introduce NiM, a carefully curated benchmark spanning diverse real-world documents including newspapers, menus, and lecture images, specifically designed to evaluate MLLMs' capability in these intricate tasks. Building on this, we further propose Spot-IT, a simple yet effective approach that enhances MLLMs capability through intelligent patch selection and Gaussian attention, motivated from how humans zoom and focus when searching documents. Our extensive experiments reveal both the capabilities and limitations of current MLLMs in handling fine-grained document understanding tasks, while demonstrating the effectiveness of our approach. Spot-IT achieves significant improvements over baseline methods, particularly in scenarios requiring precise detail extraction from complex layouts.

[Arxiv](https://arxiv.org/abs/2508.05053)