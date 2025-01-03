# ELAICHI: 通过处理罕见和低频字符二元组来提升低资源TTS性能

发布时间：2024年10月23日

`其他

理由：这篇论文主要讨论的是文本到语音（TTS）技术的改进，特别是针对缺乏高质量数据的语言。虽然提到了大规模模型和知识蒸馏，但核心内容并不涉及大型语言模型（LLM）的理论、应用、代理（Agent）或检索增强生成（RAG）。因此，将其分类为“其他”更为合适。` `语音合成`

> ELAICHI: Enhancing Low-resource TTS by Addressing Infrequent and Low-frequency Character Bigrams

# 摘要

> # 摘要
近年来，文本到语音（TTS）技术的进步使得英语语音更加自然，这主要得益于大规模高质量网络数据的支持。然而，许多其他语言因缺乏此类资源，只能依赖有限的录音室质量数据，导致合成语音常出现可懂度问题，尤其是低频字符二元组。本文提出三种解决方案：首先，利用语言或地理相关语言的高质量数据提升目标语言的TTS效果；其次，通过去噪和语音增强模型精炼非录音室环境下的低质量自动语音识别（ASR）数据；第三，使用合成数据从大规模模型中进行知识蒸馏，生成更稳健的输出。我们在印地语上的实验表明，可懂度问题显著减少，人类评估者也验证了这一点。我们建议将这种方法作为缺乏高质量数据语言的替代方案，使它们能够共享资源，共同受益。

> Recent advancements in Text-to-Speech (TTS) technology have led to natural-sounding speech for English, primarily due to the availability of large-scale, high-quality web data. However, many other languages lack access to such resources, relying instead on limited studio-quality data. This scarcity results in synthesized speech that often suffers from intelligibility issues, particularly with low-frequency character bigrams. In this paper, we propose three solutions to address this challenge. First, we leverage high-quality data from linguistically or geographically related languages to improve TTS for the target language. Second, we utilize low-quality Automatic Speech Recognition (ASR) data recorded in non-studio environments, which is refined using denoising and speech enhancement models. Third, we apply knowledge distillation from large-scale models using synthetic data to generate more robust outputs. Our experiments with Hindi demonstrate significant reductions in intelligibility issues, as validated by human evaluators. We propose this methodology as a viable alternative for languages with limited access to high-quality data, enabling them to collectively benefit from shared resources.

[Arxiv](https://arxiv.org/abs/2410.17901)