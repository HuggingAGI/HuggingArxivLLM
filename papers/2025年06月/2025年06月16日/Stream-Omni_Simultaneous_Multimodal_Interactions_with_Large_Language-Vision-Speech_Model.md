# Stream-Omni：实现大型语言-视觉-语音模型的实时多模态交互体验

发布时间：2025年06月16日

`LLM应用` `多模态模型` `交互技术`

> Stream-Omni: Simultaneous Multimodal Interactions with Large Language-Vision-Speech Model

# 摘要

> GPT-4o-like大型多模态模型（LMMs）的出现推动了多模态交互技术的革新，旨在更灵活地整合文本、视觉和语音信息。现有的LMMs通常通过沿序列维度拼接各模态的表示，并将其输入LLM主干进行处理。然而，这种拼接方式虽看似直接，却高度依赖大规模数据来实现模态对齐。本文提出Stream-Omni，一个具备高效模态对齐能力的大型语言-视觉-语音模型，能够同时支持多种模态组合下的交互。Stream-Omni采用LLM作为主干，并基于各模态间的关系实现视觉和语音与文本的对齐。对于与文本语义互补的视觉信息，Stream-Omni采用序列维度拼接技术实现视觉-文本对齐；而对于与文本语义一致的语音信息，则引入基于CTC的层维度映射技术实现语音-文本对齐。这种设计使Stream-Omni在更少数据（尤其是语音数据）的情况下也能实现高效的模态对齐，从而将文本能力迁移至其他模态。实验结果表明，Stream-Omni在视觉理解、语音交互和视觉 grounded 语音交互任务中表现优异。此外，得益于层维度映射技术，Stream-Omni在语音交互过程中能够同时输出中间文本结果（如ASR转录和模型响应），为用户提供更加全面的多模态交互体验。

> The emergence of GPT-4o-like large multimodal models (LMMs) has raised the exploration of integrating text, vision, and speech modalities to support more flexible multimodal interaction. Existing LMMs typically concatenate representation of modalities along the sequence dimension and feed them into a large language model (LLM) backbone. While sequence-dimension concatenation is straightforward for modality integration, it often relies heavily on large-scale data to learn modality alignments. In this paper, we aim to model the relationships between modalities more purposefully, thereby achieving more efficient and flexible modality alignments. To this end, we propose Stream-Omni, a large language-vision-speech model with efficient modality alignments, which can simultaneously support interactions under various modality combinations. Stream-Omni employs LLM as the backbone and aligns the vision and speech to the text based on their relationships. For vision that is semantically complementary to text, Stream-Omni uses sequence-dimension concatenation to achieve vision-text alignment. For speech that is semantically consistent with text, Stream-Omni introduces a CTC-based layer-dimension mapping to achieve speech-text alignment. In this way, Stream-Omni can achieve modality alignments with less data (especially speech), enabling the transfer of text capabilities to other modalities. Experiments on various benchmarks demonstrate that Stream-Omni achieves strong performance on visual understanding, speech interaction, and vision-grounded speech interaction tasks. Owing to the layer-dimensional mapping, Stream-Omni can simultaneously provide intermediate text outputs (such as ASR transcriptions and model responses) during speech interaction, offering users a comprehensive multimodal experience.

[Arxiv](https://arxiv.org/abs/2506.13642)