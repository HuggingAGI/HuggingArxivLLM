# TACOS：时间对齐的音频字幕为语言-音频预训练而设计

发布时间：2025年05月12日

`LLM应用` `音频技术` `跨媒体技术`

> TACOS: Temporally-aligned Audio CaptiOnS for Language-Audio Pretraining

# 摘要

> 将音频与文本描述相关联对于预训练、零样本分类、音频检索、音频字幕生成以及基于文本的音频生成等多种任务具有重要意义。现有的对比语言-音频预训练模型通常使用全局、片段级别的描述进行训练，这些描述仅提供较弱的时间监督。我们假设，类似于CLAP的语言-音频模型——特别是如果它们需要生成帧级别嵌入——将受益于更强的时间监督。为了验证这一假设，我们从Freesound精心整理了一个全新的数据集，包含约12,000个音频记录，每个记录都附有单句自由文本描述，并与音频记录中的特定时间段相关联。我们利用大型语言模型清理这些标注，去除不可闻事件、转录语音、拼写错误以及标注者语言偏见的提及。我们进一步提出了一种基于帧的对比训练策略，旨在学习将文本描述与音频记录中的时间区域对齐，并在AudioSet Strong基准上证明，与仅基于全局字幕训练的模型相比，我们的模型在时间文本-音频对齐能力方面表现更优。该数据集和我们的源代码分别在Zenodo和GitHub上提供。

> Learning to associate audio with textual descriptions is valuable for a range of tasks, including pretraining, zero-shot classification, audio retrieval, audio captioning, and text-conditioned audio generation. Existing contrastive language-audio pretrained models are typically trained using global, clip-level descriptions, which provide only weak temporal supervision. We hypothesize that CLAP-like language-audio models - particularly, if they are expected to produce frame-level embeddings - can benefit from a stronger temporal supervision. To confirm our hypothesis, we curate a novel dataset of approximately 12,000 audio recordings from Freesound, each annotated with single-sentence free-text descriptions linked to a specific temporal segment in an audio recording. We use large language models to clean these annotations by removing references to non-audible events, transcribed speech, typos, and annotator language bias. We further propose a frame-wise contrastive training strategy that learns to align text descriptions with temporal regions in an audio recording and demonstrate that our model has better temporal text-audio alignment abilities compared to models trained only on global captions when evaluated on the AudioSet Strong benchmark. The dataset and our source code are available on Zenodo and GitHub, respectively.

[Arxiv](https://arxiv.org/abs/2505.07609)