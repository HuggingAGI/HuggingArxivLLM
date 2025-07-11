# SecureSpeech：基于提示的说话人与内容保护机制

发布时间：2025年07月10日

`LLM应用` `语音处理` `隐私保护`

> SecureSpeech: Prompt-based Speaker and Content Protection

# 摘要

> 随着身份盗窃和语音内容中说话人重新识别引发的隐私担忧日益增加，本文提出了一种基于提示的语音生成管道，实现说话人身份和所说内容的双重匿名化。具体而言，我们通过1)生成不可追溯到原始说话人的身份（受描述符控制）；2)利用命名实体识别模型和大型语言模型替换文本中的敏感内容来实现这一目标。该管道结合匿名化的说话人身份和文本，通过文本到语音合成模型生成高保真且隐私友好的语音。实验结果表明，在保持内容完整性和音频质量的同时，实现了显著的隐私保护效果。此外，本文还探讨了不同说话人描述对生成语音效用和隐私的影响，以识别潜在偏见。

> Given the increasing privacy concerns from identity theft and the re-identification of speakers through content in the speech field, this paper proposes a prompt-based speech generation pipeline that ensures dual anonymization of both speaker identity and spoken content. This is addressed through 1) generating a speaker identity unlinkable to the source speaker, controlled by descriptors, and 2) replacing sensitive content within the original text using a name entity recognition model and a large language model. The pipeline utilizes the anonymized speaker identity and text to generate high-fidelity, privacy-friendly speech via a text-to-speech synthesis model. Experimental results demonstrate an achievement of significant privacy protection while maintaining a decent level of content retention and audio quality. This paper also investigates the impact of varying speaker descriptions on the utility and privacy of generated speech to determine potential biases.

[Arxiv](https://arxiv.org/abs/2507.07799)