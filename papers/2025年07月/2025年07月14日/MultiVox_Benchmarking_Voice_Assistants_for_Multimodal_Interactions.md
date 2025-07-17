# # MultiVox：多模态交互语音助手的基准评测

发布时间：2025年07月14日

`LLM应用` `人工智能`

> MultiVox: Benchmarking Voice Assistants for Multimodal Interactions

# 摘要

> 大型语言模型（LLMs）的迅猛发展让全能模型摇身一变成为能理解口语对话的语音助手。这些模型不仅能处理文本，还能驾驭语音、视觉等多模态输入，实现更富语境感知的交互体验。然而，现有的基准测试在全面评估这些模型生成语境感知响应的能力时显得力不从心，尤其在隐性理解细微语音特征（如音调、情感、音色和音量）或环境声学语境（如背景声音）方面更是捉襟见肘。此外，它们在评估模型将副语言线索与互补视觉信号相结合以生成响应的能力方面也稍显不足。为填补这一空白，我们推出了MultiVox——首个全能语音助手基准，旨在评估语音助手整合语音和视觉线索（包括副语言语音特征）的能力，从而实现真正意义上的多模态理解。MultiVox收录了1000个由人工标注和录制的语音对话，涵盖了丰富的副语言特征以及多样化的视觉线索，如图像和视频。通过对9个最先进模型的评估，我们发现，尽管人类在这些任务中表现出色，但当前模型在生成基于语境的响应方面仍面临持续挑战。

> The rapid progress of Large Language Models (LLMs) has empowered omni models to act as voice assistants capable of understanding spoken dialogues. These models can process multimodal inputs beyond text, such as speech and visual data, enabling more context-aware interactions. However, current benchmarks fall short in comprehensively evaluating how well these models generate context-aware responses, particularly when it comes to implicitly understanding fine-grained speech characteristics, such as pitch, emotion, timbre, and volume or the environmental acoustic context such as background sounds. Additionally, they inadequately assess the ability of models to align paralinguistic cues with complementary visual signals to inform their responses. To address these gaps, we introduce MultiVox, the first omni voice assistant benchmark designed to evaluate the ability of voice assistants to integrate spoken and visual cues including paralinguistic speech features for truly multimodal understanding. Specifically, MultiVox includes 1000 human-annotated and recorded speech dialogues that encompass diverse paralinguistic features and a range of visual cues such as images and videos. Our evaluation on 9 state-of-the-art models reveals that, although humans excel at these tasks, current models consistently struggle to produce contextually grounded responses.

[Arxiv](https://arxiv.org/abs/2507.10859)