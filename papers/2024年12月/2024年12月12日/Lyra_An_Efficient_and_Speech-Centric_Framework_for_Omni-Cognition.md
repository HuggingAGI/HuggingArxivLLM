# Lyra：一个高效且聚焦于语音的全认知框架

发布时间：2024年12月12日

`LLM应用` `多模态`

> Lyra: An Efficient and Speech-Centric Framework for Omni-Cognition

# 摘要

> 随着多模态大型语言模型（MLLMs）不断演进，突破单领域能力的限制，以满足对更全能、更高效的人工智能的需求，这一点至关重要。然而，以往的全能模型在语音方面探索不足，忽视了其与多模态的融合。我们推出了 Lyra，这是一款高效的 MLLM，提升了多模态能力，涵盖先进的长语音理解、声音理解、跨模态效率以及无缝语音交互。为达成效率和以语音为核心的能力，Lyra 运用了三项策略：（1）借助现有的开源大型模型和所提出的多模态 LoRA，降低训练成本和数据需求；（2）采用潜在的多模态正则化器和提取器，强化语音与其他模态的关系，进而提升模型性能；（3）构建一个高质量、大规模的数据集，包含 150 万个多模态（语言、视觉、音频）数据样本和 12000 个长语音样本，让 Lyra 能够处理复杂的长语音输入，并实现更强大的全能认知。和其他全能方法相比，Lyra 在各类视觉语言、视觉语音和语音语言基准测试中均达到了领先水平，同时使用的计算资源更少，训练数据也更少。

> As Multi-modal Large Language Models (MLLMs) evolve, expanding beyond single-domain capabilities is essential to meet the demands for more versatile and efficient AI. However, previous omni-models have insufficiently explored speech, neglecting its integration with multi-modality. We introduce Lyra, an efficient MLLM that enhances multimodal abilities, including advanced long-speech comprehension, sound understanding, cross-modality efficiency, and seamless speech interaction. To achieve efficiency and speech-centric capabilities, Lyra employs three strategies: (1) leveraging existing open-source large models and a proposed multi-modality LoRA to reduce training costs and data requirements; (2) using a latent multi-modality regularizer and extractor to strengthen the relationship between speech and other modalities, thereby enhancing model performance; and (3) constructing a high-quality, extensive dataset that includes 1.5M multi-modal (language, vision, audio) data samples and 12K long speech samples, enabling Lyra to handle complex long speech inputs and achieve more robust omni-cognition. Compared to other omni-methods, Lyra achieves state-of-the-art performance on various vision-language, vision-speech, and speech-language benchmarks, while also using fewer computational resources and less training data.

[Arxiv](https://arxiv.org/abs/2412.09501)