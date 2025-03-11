# ARMOR v0.1：通过非对称协同作用，助力自回归多模态理解模型实现交错式多模态生成

发布时间：2025年03月09日

`LLM应用` `视觉与语言` `多模态生成`

> ARMOR v0.1: Empowering Autoregressive Multimodal Understanding Model with Interleaved Multimodal Generation via Asymmetric Synergy

# 摘要

> 近年来，统一模型（UniMs）在视觉与语言领域的多模态理解和生成方面吸引了广泛关注。然而，现有的UniMs在生成交错文本-图像内容方面常常表现不佳。我们提出了一种名为ARMOR的高效且纯粹的自回归框架，通过微调现有的多模态大型语言模型（MLLMs），实现了多模态理解和生成的双重能力。具体而言，ARMOR从以下三个角度对现有MLLMs进行了扩展：（1）在模型架构方面，我们引入了一种带有前向切换机制的非对称编码器-解码器架构，统一了文本和视觉模态的嵌入空间，支持自然的文本-图像交错生成，同时保持极低的计算开销。（2）在训练数据方面，我们精心整理并收集了一个高质量的交错数据集，用于微调MLLMs。（3）在训练算法方面，我们提出了一种“生成什么或如何生成”的算法，通过基于收集数据集的三个渐进训练阶段，赋予现有MLLMs多模态生成能力，同时保留其多模态理解能力。实验结果表明，ARMOR能够将现有的MLLMs升级为具备出色图像生成能力的UniMs，且仅需有限的训练资源。我们的代码即将发布，地址为https://armor.github.io。

> Unified models (UniMs) for multimodal understanding and generation have recently received much attention in the area of vision and language. Existing UniMs are designed to simultaneously learn both multimodal understanding and generation capabilities, demanding substantial computational resources, and often struggle to generate interleaved text-image. We present ARMOR, a resource-efficient and pure autoregressive framework that achieves both understanding and generation by fine-tuning existing multimodal large language models (MLLMs). Specifically, ARMOR extends existing MLLMs from three perspectives: (1) For model architecture, an asymmetric encoder-decoder architecture with a forward-switching mechanism is introduced to unify embedding space integrating textual and visual modalities for enabling natural text-image interleaved generation with minimal computational overhead. (2) For training data, a meticulously curated, high-quality interleaved dataset is collected for fine-tuning MLLMs. (3) For the training algorithm, we propose a ``what or how to generate" algorithm to empower existing MLLMs with multimodal generation capabilities while preserving their multimodal understanding capabilities, through three progressive training stages based on the collected dataset. Experimental results demonstrate that ARMOR upgrades existing MLLMs to UniMs with promising image generation capabilities, using limited training resources. Our code will be released soon at https://armor.github.io.

[Arxiv](https://arxiv.org/abs/2503.06542)