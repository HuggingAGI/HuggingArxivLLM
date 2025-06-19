# 指向性思维：面向多说话者语音识别的语音大语言模型

发布时间：2025年06月17日

`LLM应用` `语音技术` `音频处理`

> Thinking in Directivity: Speech Large Language Model for Multi-Talker Directional Speech Recognition

# 摘要

> 最近研究表明，通过音频编码提示大型语言模型（LLM）能够实现有效的语音识别能力。然而，语音LLMs在理解并处理带有空间线索的多通道音频方面的潜力仍是一个相对未被深入研究的领域。在本研究中，我们提出了Directional-SpeechLlama这一创新方法，该方法利用智能眼镜的麦克风阵列实现方向性语音识别、声源定位以及旁听者串音抑制。为了增强模型对方向性的理解能力，我们提出了两个关键技术：序列化方向输出训练（S-DOT）和对比方向数据增强（CDDA）。实验结果表明，我们的Directional-SpeechLlama能够有效捕捉文本线索与空间音频之间的关系，在语音识别和声源定位任务中均表现出色。

> Recent studies have demonstrated that prompting large language models (LLM) with audio encodings enables effective speech recognition capabilities. However, the ability of Speech LLMs to comprehend and process multi-channel audio with spatial cues remains a relatively uninvestigated area of research. In this work, we present directional-SpeechLlama, a novel approach that leverages the microphone array of smart glasses to achieve directional speech recognition, source localization, and bystander cross-talk suppression. To enhance the model's ability to understand directivity, we propose two key techniques: serialized directional output training (S-DOT) and contrastive direction data augmentation (CDDA). Experimental results show that our proposed directional-SpeechLlama effectively captures the relationship between textual cues and spatial audio, yielding strong performance in both speech recognition and source localization tasks.

[Arxiv](https://arxiv.org/abs/2506.14973)