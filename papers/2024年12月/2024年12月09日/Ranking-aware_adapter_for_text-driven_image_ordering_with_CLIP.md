# 用于基于文本借助 CLIP 进行图像排序的排名感知适配器

发布时间：2024年12月09日

`LLM应用` `视觉语言模型`

> Ranking-aware adapter for text-driven image ordering with CLIP

# 摘要

> 近期，视觉语言模型（VLMs）取得了重大进展，在诸如面部年龄估计和图像质量评估等需要定量概念的下游任务中表现出色，使得 VLMs 能够用于图像排名和检索等应用。然而，现有的研究往往聚焦于基于单个图像的推理，且严重依赖文本提示，这限制了其从多个图像中获取全面理解的能力。为此，我们提出了一种既有效又高效的方法，将 CLIP 模型重构为学习排序任务，并引入了一个轻量级适配器来增强 CLIP 用于文本引导的图像排名。具体而言，我们的方法融入了可学习的提示，以适应新的排名指令，还带有具备排名感知注意力的辅助分支，借助文本条件下的视觉差异为图像排名提供额外监督。我们的排名感知适配器在各类任务中始终优于微调的 CLIP，与针对特定任务（如面部年龄估计和图像质量评估）设计的先进模型相比，也取得了有竞争力的结果。总之，我们的方法主要专注于用单个指令对图像进行排名，这提供了一种自然且通用的从图像间视觉差异中学习的方式，无需为各个任务定制大量文本提示。代码获取地址：https://github.com/uynaes/RankingAwareCLIP 。

> Recent advances in vision-language models (VLMs) have made significant progress in downstream tasks that require quantitative concepts such as facial age estimation and image quality assessment, enabling VLMs to explore applications like image ranking and retrieval. However, existing studies typically focus on the reasoning based on a single image and heavily depend on text prompting, limiting their ability to learn comprehensive understanding from multiple images. To address this, we propose an effective yet efficient approach that reframes the CLIP model into a learning-to-rank task and introduces a lightweight adapter to augment CLIP for text-guided image ranking. Specifically, our approach incorporates learnable prompts to adapt to new instructions for ranking purposes and an auxiliary branch with ranking-aware attention, leveraging text-conditioned visual differences for additional supervision in image ranking. Our ranking-aware adapter consistently outperforms fine-tuned CLIPs on various tasks and achieves competitive results compared to state-of-the-art models designed for specific tasks like facial age estimation and image quality assessment. Overall, our approach primarily focuses on ranking images with a single instruction, which provides a natural and generalized way of learning from visual differences across images, bypassing the need for extensive text prompts tailored to individual tasks. Code is available: https://github.com/uynaes/RankingAwareCLIP.

[Arxiv](https://arxiv.org/abs/2412.06760)