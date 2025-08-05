# 从对比到共性：基于音频共性字幕提升多模态 LLM 的跨模态理解能力

发布时间：2025年08月03日

`LLM应用` `语音处理` `音乐技术`

> From Contrast to Commonality: Audio Commonality Captioning for Enhanced Audio-Text Cross-modal Understanding in Multimodal LLMs

# 摘要

> 音频字幕（AC）在多模态大语言模型（MLLMs）的预训练和微调中，对提升音频-文本跨模态理解至关重要。近期研究提出的音频差异字幕（ADC）通过多音频输入，鼓励模型描述差异，促进细致的音频辨别。然而，尽管ADC在差异识别和详细辨别上表现出色，但其在输入音频与输出字幕间引入了显著语义差距，偏离AC风格描述，导致微调过程中的灾难性遗忘。为解决此问题，我们提出了音频共同性字幕（ACC），一种更具挑战性但更温和的方法，鼓励模型捕捉音频片段的共享语义，而非强调差异。实验结果表明，ACC不仅在主要字幕基准测试中表现优异，还在语音和音乐相关的多样化下游任务中更好地保留了通用能力，如声⾳分类（VSC）、语⾳情感识别（SER）、乐器分类（MIC）和音乐风格分类（MGC）。这证实了ACC有助于更强大的跨模态理解，并在MLLMs中实现了泛化与任务特定性能的更好平衡。

> Audio Captioning (AC) plays a pivotal role in enhancing audio-text cross-modal understanding during the pretraining and finetuning of multimodal large language models (MLLMs). To further strengthen this alignment, recent works have proposed Audio Difference Captioning (ADC), which takes multiple audio inputs and encourages the model to describe their differences, thereby promoting fine-grained audio discrimination. However, despite its effectiveness in enabling difference-telling and detailed discrimination, ADC introduces a notable semantic gap between the input audios-often rich in diverse sound events-and the relatively brief, difference-focused output captions. This deviation from AC-style descriptions leads to a mismatch with the pretraining objective, resulting in catastrophic forgetting during finetuning. To mitigate this issue, we propose Audio Commonality Captioning (ACC), a comparably challenging but gentler alternative that encourages the model to capture the shared semantics across audio clips rather than emphasizing their detailed differences. Experimental results demonstrate that ACC not only effectively enhances audio-text understanding on primary captioning benchmarks but also better preserves general capabilities across diverse speech and music-related downstream tasks, such as vocal sound classification (VSC), speech emotion recognition (SER), musical instrument classification (MIC), and music genre classification (MGC), compared to ADC. These findings validate that ACC contributes to more robust cross-modal understanding and achieves a better balance between generalization and task-specific performance in the context of MLLMs.

[Arxiv](https://arxiv.org/abs/2508.01659)