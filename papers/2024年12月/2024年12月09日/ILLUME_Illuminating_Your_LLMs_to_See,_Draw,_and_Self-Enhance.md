# ILLUME：点亮您的大型语言模型，助其观察、绘制和自我提升

发布时间：2024年12月09日

`LLM应用` `多模态` `语言模型`

> ILLUME: Illuminating Your LLMs to See, Draw, and Self-Enhance

# 摘要

> 在本文中，我们推出了 ILLUME，这是一个统一的多模态大型语言模型（MLLM），它借助统一的下一个标记预测公式，在单个大型语言模型里实现了多模态理解与生成能力的无缝融合。为应对图像 - 文本对齐通常所需的庞大数据集规模，我们提出通过设计融入语义信息的视觉标记器和渐进式多阶段训练流程来提升数据效率。此方法将预训练的数据集规模缩减至仅 1500 万——比通常所需少了四倍有余——同时在与现有统一 MLLM（如 Janus）的对比中，实现了颇具竞争力甚至更出色的性能。另外，为推动在以往工作中未得到充分挖掘的理解和生成能力之间的协同强化，我们引入了一种新颖的自增强多模态对齐方案。该方案监督 MLLM 自行评估文本描述与自身生成图像之间的一致性，助力模型更精准地解读图像，避免因图像生成中的不对齐而造成不切实际和错误的预测。基于大量实验，我们提出的 ILLUME 表现出众，在多模态理解、生成和编辑的各类基准测试中，能与最先进的统一 MLLM 和专业模型一较高下。

> In this paper, we introduce ILLUME, a unified multimodal large language model (MLLM) that seamlessly integrates multimodal understanding and generation capabilities within a single large language model through a unified next-token prediction formulation. To address the large dataset size typically required for image-text alignment, we propose to enhance data efficiency through the design of a vision tokenizer that incorporates semantic information and a progressive multi-stage training procedure. This approach reduces the dataset size to just 15M for pretraining -- over four times fewer than what is typically needed -- while achieving competitive or even superior performance with existing unified MLLMs, such as Janus. Additionally, to promote synergistic enhancement between understanding and generation capabilities, which is under-explored in previous works, we introduce a novel self-enhancing multimodal alignment scheme. This scheme supervises the MLLM to self-assess the consistency between text descriptions and self-generated images, facilitating the model to interpret images more accurately and avoid unrealistic and incorrect predictions caused by misalignment in image generation. Based on extensive experiments, our proposed ILLUME stands out and competes with state-of-the-art unified MLLMs and specialized models across various benchmarks for multimodal understanding, generation, and editing.

[Arxiv](https://arxiv.org/abs/2412.06673)