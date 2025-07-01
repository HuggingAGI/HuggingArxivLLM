# VAP-Diffusion：借助多模态大语言模型丰富描述，实现更优质的医学图像生成

发布时间：2025年06月30日

`LLM应用` `医学图像生成`

> VAP-Diffusion: Enriching Descriptions with MLLMs for Enhanced Medical Image Generation

# 摘要

> 医学图像的生成需要丰富的属性信息，因为其外观受多种潜在因素影响。例如，生成皮肤病变图像不仅需要诊断信息，还需要形状、大小、质地和颜色等细节描述。然而，这些详细描述往往难以获取。为此，我们提出了一种名为VAP-Diffusion的框架，利用多模态大语言模型（MLLMs）的外部知识，提升医学图像生成的质量和多样性。首先，我们设计了一系列遵循思维链的提示，用于从MLLMs中提取无幻觉的描述，涵盖皮肤病、结直肠和胸部X光片等多种医学成像任务。这些描述在训练时被使用，并按类别存储。在测试阶段，系统会随机从对应类别中检索描述进行推理。此外，为确保生成器在面对未见过的描述组合时仍能保持稳定，我们引入了Prototype Condition Mechanism，限制测试嵌入与训练嵌入保持相似。实验结果表明，VAP-Diffusion在四种数据集上的三种常见医学成像任务中均表现出色。

> As the appearance of medical images is influenced by multiple underlying factors, generative models require rich attribute information beyond labels to produce realistic and diverse images. For instance, generating an image of skin lesion with specific patterns demands descriptions that go beyond diagnosis, such as shape, size, texture, and color. However, such detailed descriptions are not always accessible. To address this, we explore a framework, termed Visual Attribute Prompts (VAP)-Diffusion, to leverage external knowledge from pre-trained Multi-modal Large Language Models (MLLMs) to improve the quality and diversity of medical image generation. First, to derive descriptions from MLLMs without hallucination, we design a series of prompts following Chain-of-Thoughts for common medical imaging tasks, including dermatologic, colorectal, and chest X-ray images. Generated descriptions are utilized during training and stored across different categories. During testing, descriptions are randomly retrieved from the corresponding category for inference. Moreover, to make the generator robust to unseen combination of descriptions at the test time, we propose a Prototype Condition Mechanism that restricts test embeddings to be similar to those from training. Experiments on three common types of medical imaging across four datasets verify the effectiveness of VAP-Diffusion.

[Arxiv](https://arxiv.org/abs/2506.23641)