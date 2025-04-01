# 在音频语言模型中，通过推理时计算扩展听觉认知能力

发布时间：2025年03月30日

`LLM应用` `音频处理` `语音技术`

> Scaling Auditory Cognition via Test-Time Compute in Audio Language Models

# 摘要

> 大型语言模型（LLMs）在自然语言处理中的卓越灵活性，激发了研究者通过开发音频大型语言模型（Audio LLMs）将其能力扩展至语音处理领域的努力。尽管Audio LLMs在语音识别与合成方面表现出色，但它们在面对现实环境中的听觉认知挑战（如音频理解与听力回溯）时，特别是在背景噪声或重叠语音存在的情况下，其表现仍有待探索。与基于文本的LLMs不同，后者可利用海量文本数据进行预训练，而Audio LLMs的再训练却因缺乏模拟真实听觉场景的数据集和获取训练标签的困难而面临挑战。虽然测试时计算（TTC）方法已提升基于文本LLMs的推理能力，但如何设计这些方法以增强Audio LLMs的听觉能力仍是一个关键难题。本研究旨在通过探索Audio LLMs的听觉认知能力，并利用TTC方法提升其能力，填补这一研究空白。我们借助一个	extit{自收集}的数据库，研究了五种Audio LLMs在听觉认知方面的表现，并提出了五种TTC方法，以提升其在推理过程中的听觉认知能力。研究发现，Audio LLMs在更具挑战性的听觉认知任务中表现欠佳。所提出的TTC方法显著增强了其认知听觉能力，为开发更灵活、更具韧性的Audio LLMs奠定了基础，使其在助听设备、语音AI助手及通信技术等实际应用中展现出巨大潜力。

> Large language models (LLMs) have shown exceptional versatility in natural language processing, prompting recent efforts to extend their multimodal capabilities to speech processing through the development of audio large language models (Audio LLMs). While Audio LLMs excel in tasks such as speech recognition and synthesis, it remains unclear how they perform when faced with the auditory cognitive challenges posed by real-world environments, such as audio comprehension and listening recall, particularly in the presence of background noise or overlapping speech. Unlike text-based LLMs, which have access to vast amounts of text data for pre-training, retraining Audio LLMs with diverse auditory cognitive scenes is difficult due to the limited datasets that simulate real-world auditory cognitive scenarios and the challenge of acquiring auditory cognitive labels for training. While test-time compute (TTC) methods have been shown to enhance the capabilities of text-based LLMs during inference, a key challenge lies in designing these TTC methods to improve the auditory capabilities of Audio LLMs. This study aims to address these two research gaps by: i) exploring the auditory cognitive capabilities of Audio LLMs, and ii) enhancing their capabilities using TTC approaches. We have investigated five different Audio LLMs for auditory cognition using a \textit{self-collected} database and have proposed five TTC approaches to enhance auditory cognitive capabilities during inference. Our findings reveal that Audio LLMs performance decreases in more challenging auditory cognitive tasks. The proposed TTC approaches significantly enhance cognitive auditory capabilities, advancing the development of more adaptable and resilient Audio LLMs for practical applications such as assistive listening devices, voice-based AI assistants, and communication technologies.

[Arxiv](https://arxiv.org/abs/2503.23395)