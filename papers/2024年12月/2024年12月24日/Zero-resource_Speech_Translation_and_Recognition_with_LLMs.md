# 利用大型语言模型实现零资源语音翻译和识别

发布时间：2024年12月24日

`LLM应用` `语音处理` `语言模型`

> Zero-resource Speech Translation and Recognition with LLMs

# 摘要

> 尽管语音处理近来有所进步，但零资源语音翻译（ST）和自动语音识别（ASR）依旧是难题。在本研究中，我们提议借助多语言大型语言模型（LLM），对模型未曾见过配对音频文本数据的语言进行 ST 和 ASR 操作。我们使用了预训练的多语言语音编码器、多语言 LLM 以及能将音频表示映射到 LLM 令牌嵌入空间的轻量级适配模块来达成此目的。我们在 ST 和 ASR 中开展了多项实验，以弄清楚如何最优地训练模型，以及哪些数据对之前未见过的语言的性能影响最大。在 ST 方面，我们的最优模型能在 CoVoST2 中为两种之前未见过的语言取得超过 23 的 BLEU 分数；在 ASR 中，我们实现了高达 28.2％的 WER。最后我们表明，我们系统的性能受限于 LLM 以所需语言输出文本的能力。

> Despite recent advancements in speech processing, zero-resource speech translation (ST) and automatic speech recognition (ASR) remain challenging problems. In this work, we propose to leverage a multilingual Large Language Model (LLM) to perform ST and ASR in languages for which the model has never seen paired audio-text data. We achieve this by using a pre-trained multilingual speech encoder, a multilingual LLM, and a lightweight adaptation module that maps the audio representations to the token embedding space of the LLM. We perform several experiments both in ST and ASR to understand how to best train the model and what data has the most impact on performance in previously unseen languages. In ST, our best model is capable to achieve BLEU scores over 23 in CoVoST2 for two previously unseen languages, while in ASR, we achieve WERs of up to 28.2\%. We finally show that the performance of our system is bounded by the ability of the LLM to output text in the desired language.

[Arxiv](https://arxiv.org/abs/2412.18566)