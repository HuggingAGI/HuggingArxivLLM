# Ola: 渐进式模态对齐，引领全模态语言模型新潮流

发布时间：2025年02月06日

`LLM应用

理由：这篇论文介绍了Ola，一个全模态语言模型，旨在理解和处理多模态数据（如图像、视频和音频）。论文的核心在于如何通过渐进式模态对齐策略来扩展语言模型的能力，使其在多模态理解任务中表现优异。虽然涉及了模型的设计和训练方法，但主要关注的是如何将LLM应用于多模态场景，并提供了具体的应用案例和实验结果。因此，这篇论文更适合归类为LLM应用。` `人工智能` `多模态学习`

> Ola: Pushing the Frontiers of Omni-Modal Language Model with Progressive Modality Alignment

# 摘要

> # 摘要
近期，大型语言模型的进展，尤其是GPT-4o的推出，激发了人们对开发能够理解多模态的全模态模型的浓厚兴趣。尽管已有一些开源方案问世，但其性能仍显著落后于专门的单模态模型。本文介绍了Ola，一个全模态语言模型，其在图像、视频和音频理解方面与专门模型相比表现优异。Ola的核心设计在于其渐进式模态对齐策略，逐步扩展语言模型的支持模态。我们的训练流程从图像和文本这两个差异最大的模态开始，随后逐步引入连接语言与音频的语音数据，以及连接所有模态的视频数据，以此扩展模型的技能集。这种渐进式学习方式使我们能够保持较小的跨模态对齐数据规模，从而降低了从现有视觉语言模型开发全模态模型的难度和成本。此外，为了提供类似GPT-4o的高级交互体验，我们还设计了一种逐句解码方案，用于流式语音生成。大量实验表明，Ola在所有模态上都超越了现有的开源全模态LLM，并在与同规模的最先进专门模型对比中表现出色。我们致力于将Ola打造成一个完全开放的全模态理解解决方案，以推动这一新兴领域的未来研究。模型权重、代码和数据已在https://github.com/Ola-Omni/Ola开源。

> Recent advances in large language models, particularly following GPT-4o, have sparked increasing interest in developing omni-modal models capable of understanding more modalities. While some open-source alternatives have emerged, there is still a notable lag behind specialized single-modality models in performance. In this paper, we present Ola, an Omni-modal language model that achieves competitive performance across image, video, and audio understanding compared to specialized counterparts. The core design of Ola lies in its progressive modality alignment strategy that extends the supporting modality of the language model progressively. Our training pipeline begins with the most distinct modalities: image and text, then gradually expands the skill sets of the model using speech data that connects language and audio knowledge, and video data that connects all modalities. The progressive learning pipeline also enables us to maintain a relatively small size of the cross-modal alignment data, making developing omni-modal from existing vision-language models easy and less costly. Moreover, to unlock an advanced interactive experience like GPT-4o, we further design a sentence-wise decoding solution for streaming speech generation. Extensive experiments demonstrate that Ola surpasses existing open omni-modal LLMs across all modalities while achieving highly competitive performance compared to state-of-the-art specialized models of similar sizes. We aim to make Ola a fully open omni-modal understanding solution to advance future research in this emerging field. Model weights, code, and data are open-sourced at https://github.com/Ola-Omni/Ola.

[Arxiv](https://arxiv.org/abs/2502.04328)