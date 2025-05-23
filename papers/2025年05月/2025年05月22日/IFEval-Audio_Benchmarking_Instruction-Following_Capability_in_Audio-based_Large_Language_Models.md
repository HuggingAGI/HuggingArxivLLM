# IFEval-Audio：评测基于音频的大型语言模型的指令遵循能力

发布时间：2025年05月22日

`LLM应用` `人工智能`

> IFEval-Audio: Benchmarking Instruction-Following Capability in Audio-based Large Language Models

# 摘要

> 大型语言模型（LLMs）在文本任务中展现出了强大的指令遵循能力。然而，当与图像或音频等非文本模态对齐后，这种能力在多模态模型中往往会下降。尽管已有研究探讨了文本和视觉-语言模型中的指令遵循性能，但基于音频的大型语言模型的指令遵循能力仍鲜有研究。为填补这一空白，我们引入了IFEval-Audio，一个专门设计用于评估音频LLM遵循指令能力的新颖评估数据集。该数据集包含280个音频-指令-答案三元组，涵盖内容、大写、符号、列表结构、长度和格式六个维度。每个示例将音频输入与文本指令配对，要求模型生成遵循指定结构的输出。我们对最先进的音频LLM在遵循涉及音频指令方面的能力进行了基准测试。该数据集已公开发布，以支持这一新兴领域的未来研究。

> Large language models (LLMs) have demonstrated strong instruction-following capabilities in text-based tasks. However, this ability often deteriorates in multimodal models after alignment with non-text modalities such as images or audio. While several recent efforts have investigated instruction-following performance in text and vision-language models, instruction-following in audio-based large language models remains largely unexplored. To bridge this gap, we introduce IFEval-Audio, a novel evaluation dataset designed to assess the ability to follow instructions in an audio LLM. IFEval-Audio contains 280 audio-instruction-answer triples across six diverse dimensions: Content, Capitalization, Symbol, List Structure, Length, and Format. Each example pairs an audio input with a text instruction, requiring the model to generate an output that follows a specified structure. We benchmark state-of-the-art audio LLMs on their ability to follow audio-involved instructions. The dataset is released publicly to support future research in this emerging area.

[Arxiv](https://arxiv.org/abs/2505.16774)