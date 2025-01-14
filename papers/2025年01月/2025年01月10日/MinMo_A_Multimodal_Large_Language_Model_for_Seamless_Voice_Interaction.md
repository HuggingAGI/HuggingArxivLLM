# MinMo: 多模态大语言模型，实现无缝语音交互

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要介绍了一个名为MinMo的多模态大型语言模型，该模型专为无缝语音交互设计，并在语音理解和生成方面取得了业界领先水平。论文详细描述了模型的训练过程、性能指标以及应用场景，如全双工对话和语音生成控制。这些内容表明该论文主要关注如何将大型语言模型应用于具体的语音交互任务，因此应归类为“LLM应用”。` `语音交互`

> MinMo: A Multimodal Large Language Model for Seamless Voice Interaction

# 摘要

> # 摘要
最近，大型语言模型（LLMs）和多模态语音-文本模型的突破性进展为无缝语音交互铺平了道路，实现了实时、自然且高度拟人的对话体验。以往的语音交互模型主要分为两类：原生模型和对齐模型。原生模型虽然在一个框架内整合了语音和文本处理，但面临序列长度不一致和预训练不足等挑战。对齐模型虽然保留了文本LLM的强大能力，但受限于小数据集和对语音任务的单一关注。为此，我们推出了MinMo，一个拥有约80亿参数的多模态大型语言模型，专为无缝语音交互设计。我们通过多阶段的语音到文本对齐、文本到语音对齐、语音到语音对齐以及双工交互对齐，在140万小时的多样化语音数据和广泛的语音任务上对MinMo进行了训练。经过多阶段训练后，MinMo在语音理解和生成的各项基准测试中均达到了业界领先水平，同时保持了文本LLM的强大能力，并支持全双工对话，即用户与系统之间的双向实时交互。此外，我们还提出了一种新颖且高效的语音解码器，在语音生成方面超越了现有模型。MinMo的增强指令跟随能力使其能够根据用户指令精确控制语音生成，涵盖情感、方言、语速等细微差别，甚至能模仿特定声音。MinMo的语音到文本延迟约为100毫秒，全双工延迟理论值为600毫秒，实际应用中约为800毫秒。MinMo项目详情请访问https://funaudiollm.github.io/minmo，代码和模型即将发布。

> Recent advancements in large language models (LLMs) and multimodal speech-text models have laid the groundwork for seamless voice interactions, enabling real-time, natural, and human-like conversations. Previous models for voice interactions are categorized as native and aligned. Native models integrate speech and text processing in one framework but struggle with issues like differing sequence lengths and insufficient pre-training. Aligned models maintain text LLM capabilities but are often limited by small datasets and a narrow focus on speech tasks. In this work, we introduce MinMo, a Multimodal Large Language Model with approximately 8B parameters for seamless voice interaction. We address the main limitations of prior aligned multimodal models. We train MinMo through multiple stages of speech-to-text alignment, text-to-speech alignment, speech-to-speech alignment, and duplex interaction alignment, on 1.4 million hours of diverse speech data and a broad range of speech tasks. After the multi-stage training, MinMo achieves state-of-the-art performance across various benchmarks for voice comprehension and generation while maintaining the capabilities of text LLMs, and also facilitates full-duplex conversation, that is, simultaneous two-way communication between the user and the system. Moreover, we propose a novel and simple voice decoder that outperforms prior models in voice generation. The enhanced instruction-following capabilities of MinMo supports controlling speech generation based on user instructions, with various nuances including emotions, dialects, and speaking rates, and mimicking specific voices. For MinMo, the speech-to-text latency is approximately 100ms, full-duplex latency is approximately 600ms in theory and 800ms in practice. The MinMo project web page is https://funaudiollm.github.io/minmo, and the code and models will be released soon.

[Arxiv](https://arxiv.org/abs/2501.06282)