# 双扩散：统一图像生成与理解

发布时间：2024年12月31日

`其他

理由：这篇论文主要讨论的是扩散模型在多模态理解与生成任务中的应用，特别是图像生成、图像描述和视觉问答等任务。虽然涉及到了多模态模型和生成任务，但并没有直接涉及大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）相关的内容。因此，将其分类为“其他”更为合适。` `计算机视觉`

> Dual Diffusion for Unified Image Generation and Understanding

# 摘要

> 扩散模型在文本生成图像领域大放异彩，但在视觉理解任务上仍稍逊一筹，这一领域目前由自回归视觉语言模型领跑。我们推出了一款大规模、全端到端的扩散模型，专攻多模态理解与生成，大幅超越了现有基于扩散的多模态模型，并首次实现了全套视觉语言建模能力。借鉴多模态扩散变换器（MM-DiT）和离散扩散语言建模的最新成果，我们采用了一种跨模态最大似然估计框架，该框架在单一损失函数下同步训练图像与文本的条件似然，并通过扩散变换器的双分支进行反向传播。此模型灵活多变，能胜任图像生成、图像描述及视觉问答等多种任务。与近期统一的图像理解与生成模型相比，我们的模型表现不俗，彰显了多模态扩散建模作为自回归下一令牌预测模型替代方案的巨大潜力。

> Diffusion models have gained tremendous success in text-to-image generation, yet still lag behind with visual understanding tasks, an area dominated by autoregressive vision-language models. We propose a large-scale and fully end-to-end diffusion model for multi-modal understanding and generation that significantly improves on existing diffusion-based multimodal models, and is the first of its kind to support the full suite of vision-language modeling capabilities. Inspired by the multimodal diffusion transformer (MM-DiT) and recent advances in discrete diffusion language modeling, we leverage a cross-modal maximum likelihood estimation framework that simultaneously trains the conditional likelihoods of both images and text jointly under a single loss function, which is back-propagated through both branches of the diffusion transformer. The resulting model is highly flexible and capable of a wide range of tasks including image generation, captioning, and visual question answering. Our model attained competitive performance compared to recent unified image understanding and generation models, demonstrating the potential of multimodal diffusion modeling as a promising alternative to autoregressive next-token prediction models.

[Arxiv](https://arxiv.org/abs/2501.00289)