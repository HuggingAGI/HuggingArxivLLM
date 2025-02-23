# MATS：一个在纯文本监督下开发的音频语言模型

发布时间：2025年02月20日

`LLM应用` `音频处理` `语言模型`

> MATS: An Audio Language Model under Text-only Supervision

# 摘要

> 基于强大大型语言模型（LLMs）构建的大型音频-语言模型（LALMs），展现出了卓越的音频理解和推理能力。然而，训练这些模型需要大量音频-语言配对语料库，这需要巨大的数据收集和训练资源投入。本文中，我们提出了MATS，一种仅使用文本监督的音频-语言多模态LLM，专注于处理多种音频任务。通过利用预训练的音频-语言对齐模型（如CLAP），我们开发了一种纯文本训练策略，将共享的音频-语言潜在空间投影到LLM的潜在空间中，从而在不依赖音频数据的情况下赋予LLM理解音频的能力。为了进一步缩小CLAP中音频与语言嵌入之间的模态差距，我们提出了“与音频强烈相关的噪声文本”（Santa）机制。Santa将音频嵌入映射到CLAP的语言嵌入空间，同时保留音频输入中的关键信息。大量实验表明，尽管MATS仅基于文本数据进行训练，但其性能与近期基于大规模音频-语言配对训练的LALMs相比仍具有竞争力。

> Large audio-language models (LALMs), built upon powerful Large Language Models (LLMs), have exhibited remarkable audio comprehension and reasoning capabilities. However, the training of LALMs demands a large corpus of audio-language pairs, which requires substantial costs in both data collection and training resources. In this paper, we propose MATS, an audio-language multimodal LLM designed to handle Multiple Audio task using solely Text-only Supervision. By leveraging pre-trained audio-language alignment models such as CLAP, we develop a text-only training strategy that projects the shared audio-language latent space into LLM latent space, endowing the LLM with audio comprehension capabilities without relying on audio data during training. To further bridge the modality gap between audio and language embeddings within CLAP, we propose the Strongly-related noisy text with audio (Santa) mechanism. Santa maps audio embeddings into CLAP language embedding space while preserving essential information from the audio input. Extensive experiments demonstrate that MATS, despite being trained exclusively on text data, achieves competitive performance compared to recent LALMs trained on large-scale audio-language pairs.

[Arxiv](https://arxiv.org/abs/2502.13433)