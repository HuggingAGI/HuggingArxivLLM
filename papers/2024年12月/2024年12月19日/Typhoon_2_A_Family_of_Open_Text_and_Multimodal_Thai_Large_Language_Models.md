# 台风 2：一个泰语开放文本和多模态大型语言模型家族

发布时间：2024年12月19日

`LLM应用` `多模态模型`

> Typhoon 2: A Family of Open Text and Multimodal Thai Large Language Models

# 摘要

> 这篇论文介绍了“台风 2”（Typhoon 2），它是一系列为泰语优化的文本和多模态大型语言模型。该系列涵盖文本、视觉和音频等模型。“台风 2 - 文本”（Typhoon2-Text）基于诸如 Llama 3 和 Qwen2 等先进的开放模型，并在英泰混合数据上进行持续预训练。我们运用多种后训练技术提升泰语性能，同时保留基础模型原有能力。我们发布了从 1 到 700 亿参数不等的多种规模的文本模型，包括基础版和指令调优版。“台风 2 - 视觉”（Typhoon2-Vision）在保留通用视觉能力（如生成图像描述）的同时，提升了泰语文档的理解能力。“台风 2 - 音频”（Typhoon2-Audio）引入了端到端的语音到语音模型架构，能够处理音频、语音和文本输入，并同时生成文本和语音输出。

> This paper introduces Typhoon 2, a series of text and multimodal large language models optimized for the Thai language. The series includes models for text, vision, and audio. Typhoon2-Text builds on state-of-the-art open models, such as Llama 3 and Qwen2, and we perform continual pre-training on a mixture of English and Thai data. We employ post-training techniques to enhance Thai language performance while preserving the base models' original capabilities. We release text models across a range of sizes, from 1 to 70 billion parameters, available in both base and instruction-tuned variants. To guardrail text generation, we release Typhoon2-Safety, a classifier enhanced for Thai cultures and language. Typhoon2-Vision improves Thai document understanding while retaining general visual capabilities, such as image captioning. Typhoon2-Audio introduces an end-to-end speech-to-speech model architecture capable of processing audio, speech, and text inputs and generating both text and speech outputs.

[Arxiv](https://arxiv.org/abs/2412.13702)