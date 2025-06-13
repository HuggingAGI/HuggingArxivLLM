# # 采用基于调度的语音文本交错训练方法，利用大语言模型实现语音到语音翻译

发布时间：2025年06月11日

`LLM应用` `语音翻译` `语音处理`

> Scheduled Interleaved Speech-Text Training for Speech-to-Speech Translation with LLMs

# 摘要

> 语音到语音翻译（S2ST）在大型语言模型（LLMs）方面取得了显著进展，这些模型通过在离散语音单元上进行微调实现。然而，从文本到语音的模态适应一直是这些方法中的一个难题。由于LLMs仅基于文本数据进行训练，因此在基于有限语音到语音数据时，它们难以适应语音模态。为了解决这一训练难题，本研究提出了一种计划交错语音-文本训练方法。我们在训练过程中使用交错的语音-文本单元，而不是单独的语音单元，其中对齐的文本标记会在单词级别进行交错。随着训练的进展，我们逐渐降低文本的比例，以促进从文本到语音的渐进式模态适应。我们通过在CVSS数据集上对LLaMA3.2-1B进行微调来开展实验评估。实验结果表明，提出的方法能够持续提升翻译性能，特别是在训练数据有限的语言上表现尤为突出。

> Speech-to-speech translation (S2ST) has been advanced with large language models (LLMs), which are fine-tuned on discrete speech units. In such approaches, modality adaptation from text to speech has been an issue. LLMs are trained on text-only data, which presents challenges to adapt them to speech modality with limited speech-to-speech data. To address the training difficulty, we propose scheduled interleaved speech--text training in this study. We use interleaved speech--text units instead of speech units during training, where aligned text tokens are interleaved at the word level. We gradually decrease the ratio of text as training progresses, to facilitate progressive modality adaptation from text to speech. We conduct experimental evaluations by fine-tuning LLaMA3.2-1B for S2ST on the CVSS dataset. We show that the proposed method consistently improves the translation performances, especially for languages with limited training data.

[Arxiv](https://arxiv.org/abs/2506.10299)