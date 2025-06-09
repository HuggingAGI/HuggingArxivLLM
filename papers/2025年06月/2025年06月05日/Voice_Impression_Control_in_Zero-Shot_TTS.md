# 零样本TTS语音印象控制

发布时间：2025年06月05日

`LLM应用` `语音合成` `人机交互`

> Voice Impression Control in Zero-Shot TTS

# 摘要

> 语音中的副语言/非语言信息对塑造听者印象至关重要。尽管零样本文本到语音（TTS）在保持说话人忠实度方面表现优异，但通过调节微妙的副语言/非语言信息来控制语音特征（即印象）仍具挑战。为此，我们开发了一种基于低维向量的语音印象控制方法，用于表示不同语音印象对（如暗-亮）的强度。实验结果表明，该方法在印象控制方面表现出色。此外，借助大型语言模型生成控制向量，我们可直接从自然语言描述中实现目标印象生成，无需手动调整。

> Para-/non-linguistic information in speech is pivotal in shaping the listeners' impression. Although zero-shot text-to-speech (TTS) has achieved high speaker fidelity, modulating subtle para-/non-linguistic information to control perceived voice characteristics, i.e., impressions, remains challenging. We have therefore developed a voice impression control method in zero-shot TTS that utilizes a low-dimensional vector to represent the intensities of various voice impression pairs (e.g., dark-bright). The results of both objective and subjective evaluations have demonstrated our method's effectiveness in impression control. Furthermore, generating this vector via a large language model enables target-impression generation from a natural language description of the desired impression, thus eliminating the need for manual optimization.

[Arxiv](https://arxiv.org/abs/2506.05688)