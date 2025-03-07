# # 构建多样化风格的文本到语音数据集

发布时间：2025年03月06日

`LLM应用` `语音处理` `TTS`

> Scaling Rich Style-Prompted Text-to-Speech Datasets

# 摘要

> 我们推出了副语言语音字幕（ParaSpeechCaps），这是一个大规模语音数据集，标注了丰富的风格字幕。虽然丰富的抽象标签（如喉音、鼻音、痛苦等）已在小型人工标注数据集中有所探索，但现有大规模数据集仅涵盖基础标签（如低音调、慢速、大声）。我们首次结合现成的文本和语音嵌入器、分类器以及音频语言模型，实现了丰富标签标注的自动扩展。ParaSpeechCaps共包含59个风格标签，涵盖说话人级别的固有标签和语句级别的情境标签。该数据集由342小时的人工标注数据（PSC-Base）和2427小时的自动标注数据（PSC-Scaled）组成。我们在ParaSpeechCaps上微调开源的风格提示TTS模型Parler-TTS，与结合现有丰富风格标签数据集的最佳基线相比，实现了显著提升的风格一致性（+7.9% 一致性 MOS）和语音质量（+15.5% 自然度 MOS）。我们对数据集设计中的多个选择进行了消融实验，为未来研究奠定了基础。我们的数据集、模型和代码已发布在https://github.com/ajd12342/paraspeechcaps。

> We introduce Paralinguistic Speech Captions (ParaSpeechCaps), a large-scale dataset that annotates speech utterances with rich style captions. While rich abstract tags (e.g. guttural, nasal, pained) have been explored in small-scale human-annotated datasets, existing large-scale datasets only cover basic tags (e.g. low-pitched, slow, loud). We combine off-the-shelf text and speech embedders, classifiers and an audio language model to automatically scale rich tag annotations for the first time. ParaSpeechCaps covers a total of 59 style tags, including both speaker-level intrinsic tags and utterance-level situational tags. It consists of 342 hours of human-labelled data (PSC-Base) and 2427 hours of automatically annotated data (PSC-Scaled). We finetune Parler-TTS, an open-source style-prompted TTS model, on ParaSpeechCaps, and achieve improved style consistency (+7.9% Consistency MOS) and speech quality (+15.5% Naturalness MOS) over the best performing baseline that combines existing rich style tag datasets. We ablate several of our dataset design choices to lay the foundation for future work in this space. Our dataset, models and code are released at https://github.com/ajd12342/paraspeechcaps .

[Arxiv](https://arxiv.org/abs/2503.04713)