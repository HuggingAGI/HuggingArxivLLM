# # 无声训练：无需语音的语音指令学习，专为低资源语言设计
一种无需语音数据的语音指令训练方法，特别针对低资源语言开发。

发布时间：2025年05月22日

`LLM应用` `语音助手` `语音识别`

> Speechless: Speech Instruction Training Without Speech for Low Resource Languages

# 摘要

> 大型语言模型 (LLM) 驱动的语音助手快速发展，凸显了语音指令数据在训练中的关键作用。尽管语音识别数据丰富，但语音指令数据却相对匮乏，这对模型理解和执行语音指令的能力至关重要。生成高质量合成语音需要优秀的文本到语音（TTS）模型，但资源匮乏的语言往往难以获取。我们的创新方法通过在语义表示层面停止合成，巧妙绕过了对TTS模型的依赖。通过将合成语义表示与预训练的Whisper编码器对齐，使LLM可以在文本指令上进行微调，同时在推理时仍能理解语音指令。这一简化的训练流程为低资源语言开发语音助手开辟了新的可能。

> The rapid growth of voice assistants powered by large language models (LLM) has highlighted a need for speech instruction data to train these systems. Despite the abundance of speech recognition data, there is a notable scarcity of speech instruction data, which is essential for fine-tuning models to understand and execute spoken commands. Generating high-quality synthetic speech requires a good text-to-speech (TTS) model, which may not be available to low resource languages. Our novel approach addresses this challenge by halting synthesis at the semantic representation level, bypassing the need for TTS. We achieve this by aligning synthetic semantic representations with the pre-trained Whisper encoder, enabling an LLM to be fine-tuned on text instructions while maintaining the ability to understand spoken instructions during inference. This simplified training process is a promising approach to building voice assistant for low-resource languages.

[Arxiv](https://arxiv.org/abs/2505.17417)