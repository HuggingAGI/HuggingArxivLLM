# EmoVoice：基于LLM的情感文本到语音模型，支持自由文本提示

发布时间：2025年04月17日

`LLM应用` `人工智能` `语音合成`

> EmoVoice: LLM-based Emotional Text-To-Speech Model with Freestyle Text Prompting

# 摘要

> 人类的语音不仅仅是单纯的信息传递，更是情感的深刻交流和人与人之间的连接。尽管文本到语音（TTS）模型已经取得了巨大进展，但对生成语音中情感表达的控制仍然是一个挑战。本研究提出了EmoVoice——一款新型情感可控TTS模型。该模型利用大型语言模型（LLMs）实现细粒度的自由风格自然语言情感控制，并采用受链条思维（CoT）和模态思维（CoM）技术启发的音素增强变体设计，使模型能够并行输出音素令牌和音频令牌，从而增强内容一致性。此外，我们还推出了EmoVoice-DB——一个高质量的40小时英语情感数据集，包含富有表现力的语音和带有自然语言描述的细粒度情感标签。在仅使用合成训练数据的情况下，EmoVoice在英语EmoVoice-DB测试集上实现了最先进的性能，并在中文Secap测试集上取得了优异表现。我们进一步研究了现有情感评估指标的可靠性及其与人类感知偏好的一致性，并探索了使用最先进的多模态LLMs GPT-4o-audio 和 Gemini 来评估情感语音。演示样本可在 https://anonymous.4open.science/r/EmoVoice-DF55 获取。数据集、代码和检查点即将公开发布。

> Human speech goes beyond the mere transfer of information; it is a profound exchange of emotions and a connection between individuals. While Text-to-Speech (TTS) models have made huge progress, they still face challenges in controlling the emotional expression in the generated speech. In this work, we propose EmoVoice, a novel emotion-controllable TTS model that exploits large language models (LLMs) to enable fine-grained freestyle natural language emotion control, and a phoneme boost variant design that makes the model output phoneme tokens and audio tokens in parallel to enhance content consistency, inspired by chain-of-thought (CoT) and modality-of-thought (CoM) techniques. Besides, we introduce EmoVoice-DB, a high-quality 40-hour English emotion dataset featuring expressive speech and fine-grained emotion labels with natural language descriptions. EmoVoice achieves state-of-the-art performance on the English EmoVoice-DB test set using only synthetic training data, and on the Chinese Secap test set using our in-house data. We further investigate the reliability of existing emotion evaluation metrics and their alignment with human perceptual preferences, and explore using SOTA multimodal LLMs GPT-4o-audio and Gemini to assess emotional speech. Demo samples are available at https://anonymous.4open.science/r/EmoVoice-DF55. Dataset, code, and checkpoints will be released.

[Arxiv](https://arxiv.org/abs/2504.12867)