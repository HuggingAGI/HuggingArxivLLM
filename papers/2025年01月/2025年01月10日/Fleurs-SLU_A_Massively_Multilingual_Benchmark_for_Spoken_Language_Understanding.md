# Fleurs-SLU: 大规模多语言口语理解基准

发布时间：2025年01月10日

`LLM应用

**理由**：这篇论文主要讨论了多语言自动语音识别（ASR）和多语言口语理解（SLU）的结合，特别是如何利用大型语言模型（LLM）来提升多语言ASR的鲁棒性。论文中提到的“结合语音转文本与后续大型语言模型分类的级联系统”直接涉及了LLM的应用，因此将其分类为LLM应用。` `语音识别` `多语言处理`

> Fleurs-SLU: A Massively Multilingual Benchmark for Spoken Language Understanding

# 摘要

> 尽管最新的多语言自动语音识别（ASR）模型声称支持数千种语言，但由于双模态语音和文本训练数据的匮乏，低资源语言的ASR表现依然不尽如人意。多语言口语理解（SLU）通过利用语言语义来弥补训练数据的不足，能够显著提升多语言ASR的鲁棒性，例如通过上下文消除歧义或利用跨语言的语义相似性。尤其对于约半数缺乏正式书写系统的语言，SLU在包容性语音技术中不可或缺。然而，目前多语言SLU的评估仍局限于意图分类或语言识别等浅层任务。为此，我们推出了Fleurs-SLU，一个涵盖102种语言的主题语音分类和92种语言的听力理解多项选择题回答的多语言SLU基准。我们在Fleurs-SLU上对端到端语音分类模型以及结合语音转文本与后续大型语言模型分类的级联系统进行了广泛评估。结果显示，级联系统在多语言SLU任务中表现更为稳健，而语音编码器在适当预训练后也能在主题分类任务中取得不俗成绩。此外，我们发现鲁棒的多语言ASR、高效的语音转文本翻译与强大的多语言SLU之间存在强相关性，凸显了声学与语义语音表示之间的协同效应。

> While recent multilingual automatic speech recognition models claim to support thousands of languages, ASR for low-resource languages remains highly unreliable due to limited bimodal speech and text training data. Better multilingual spoken language understanding (SLU) can strengthen massively the robustness of multilingual ASR by levering language semantics to compensate for scarce training data, such as disambiguating utterances via context or exploiting semantic similarities across languages. Even more so, SLU is indispensable for inclusive speech technology in roughly half of all living languages that lack a formal writing system. However, the evaluation of multilingual SLU remains limited to shallower tasks such as intent classification or language identification. To address this, we present Fleurs-SLU, a multilingual SLU benchmark that encompasses topical speech classification in 102 languages and multiple-choice question answering through listening comprehension in 92 languages. We extensively evaluate both end-to-end speech classification models and cascaded systems that combine speech-to-text transcription with subsequent classification by large language models on Fleurs-SLU. Our results show that cascaded systems exhibit greater robustness in multilingual SLU tasks, though speech encoders can achieve competitive performance in topical speech classification when appropriately pre-trained. We further find a strong correlation between robust multilingual ASR, effective speech-to-text translation, and strong multilingual SLU, highlighting the mutual benefits between acoustic and semantic speech representations.

[Arxiv](https://arxiv.org/abs/2501.06117)