# # AC/DC：通过对话延续实现的基于LLM的音频理解

发布时间：2025年06月11日

`LLM应用` `音频处理` `对话系统`

> AC/DC: LLM-based Audio Comprehension via Dialogue Continuation

# 摘要

> 我们提出了一种基于大型语言模型 (LLMs) 对话延续能力的指令跟随音频理解模型。与直接生成目标字幕的传统方法不同，我们采用对话延续训练，将输入字幕视为对话触发器，生成相应的回应。这种训练方式有效缓解了字幕变体问题，使模型能够捕捉字幕的深层含义。因此，即使仅基于音频字幕数据集训练，我们的模型也能实现无需多任务指令微调的零样本指令跟随能力。在 AudioCaps、WavCaps 和 Clotho 数据集上进行的 AudioBench 音频场景问答测试中，实验结果验证了我们的模型能够有效遵循多种未见指令。

> We propose an instruction-following audio comprehension model that leverages the dialogue continuation ability of large language models (LLMs). Instead of directly generating target captions in training data, the proposed method trains a model to produce responses as if the input caption triggered a dialogue. This dialogue continuation training mitigates the caption variation problem. Learning to continue a dialogue effectively captures the caption's meaning beyond its surface-level words. As a result, our model enables zero-shot instruction-following capability without multitask instruction tuning, even trained solely on audio captioning datasets. Experiments on AudioCaps, WavCaps, and Clotho datasets with AudioBench audio-scene question-answering tests demonstrate our model's ability to follow various unseen instructions.

[Arxiv](https://arxiv.org/abs/2506.10312)