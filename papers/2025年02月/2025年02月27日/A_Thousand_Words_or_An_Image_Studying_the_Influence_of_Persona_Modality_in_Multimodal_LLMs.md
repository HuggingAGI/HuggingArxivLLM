# 一图胜千言：多模态大语言模型中人物模态的影响研究

发布时间：2025年02月27日

`LLM应用` `虚拟助手` `人工智能`

> A Thousand Words or An Image: Studying the Influence of Persona Modality in Multimodal LLMs

# 摘要

> 大型语言模型 (LLMs) 在体现多样化人格方面取得了显著进展，不仅提升了对话代理和虚拟助手的效果，还在处理多模态信息方面实现了突破。然而，尽管人类人格可以通过文本和图像表达，但不同模态对 LLM 体现的影响仍待深入探索。本文研究了不同模态如何影响多模态 LLM 中人格的表达能力。为此，我们创建了一个包含 40 种多样的模态平行数据集，涵盖年龄、性别、职业和位置等维度。该数据集包含四种模态：仅图像、仅文本、图像与简短文本的组合，以及视觉化风格化的排版图像。我们还设计了一个包含 60 个问题和指标的评估框架，全面评估 LLMs 在不同场景中体现人格的效果。实验结果显示，详细文本描述的人格更具语言特色，而排版图像则更能保持人格一致性。研究发现 LLMs 倾向于忽略图像传达的人格细节，揭示了现有模型的局限性，为未来研究提供了方向。我们在 https://github.com/claws-lab/persona-modality 上开源了数据和代码。

> Large language models (LLMs) have recently demonstrated remarkable advancements in embodying diverse personas, enhancing their effectiveness as conversational agents and virtual assistants. Consequently, LLMs have made significant strides in processing and integrating multimodal information. However, even though human personas can be expressed in both text and image, the extent to which the modality of a persona impacts the embodiment by the LLM remains largely unexplored. In this paper, we investigate how do different modalities influence the expressiveness of personas in multimodal LLMs. To this end, we create a novel modality-parallel dataset of 40 diverse personas varying in age, gender, occupation, and location. This consists of four modalities to equivalently represent a persona: image-only, text-only, a combination of image and small text, and typographical images, where text is visually stylized to convey persona-related attributes. We then create a systematic evaluation framework with 60 questions and corresponding metrics to assess how well LLMs embody each persona across its attributes and scenarios. Comprehensive experiments on $5$ multimodal LLMs show that personas represented by detailed text show more linguistic habits, while typographical images often show more consistency with the persona. Our results reveal that LLMs often overlook persona-specific details conveyed through images, highlighting underlying limitations and paving the way for future research to bridge this gap. We release the data and code at https://github.com/claws-lab/persona-modality .

[Arxiv](https://arxiv.org/abs/2502.20504)