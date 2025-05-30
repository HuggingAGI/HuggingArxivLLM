# LLM-Synth4KWS：用于自定义关键词检测的可扩展自动混淆数据生成与合成

发布时间：2025年05月28日

`LLM应用` `语音技术` `人工智能`

> LLM-Synth4KWS: Scalable Automatic Generation and Synthesis of Confusable Data for Custom Keyword Spotting

# 摘要

> 自定义关键词检测（KWS）能够实时识别用户自定义的语音关键词，其工作原理是通过对比语音注册和输入音频的嵌入特征。目前最先进的自定义KWS模型通常采用对比学习方法训练，使用随机采样自训练数据集的带关键词 utterances。然而，这些模型在处理易混淆关键词（如“blue”和“glue”）时表现欠佳。

本文提出了一种有效的训练增强方法：通过从大语言模型（LLMs）中生成并分组关键词，并结合文本到语音（TTS）引擎生成多样化发音风格的语音信号。为了更好地衡量用户在易混淆KWS上的体验，我们引入了一个新的关键指标c-AUC（即从易混淆组计算的平均DET曲线面积）。该方法具有高度可扩展性且无需人工成本，在Speech Commands测试集上将AUC提升了3.7%，c-AUC提升了11.3%。


> Custom keyword spotting (KWS) allows detecting user-defined spoken keywords from streaming audio. This is achieved by comparing the embeddings from voice enrollments and input audio. State-of-the-art custom KWS models are typically trained contrastively using utterances whose keywords are randomly sampled from training dataset. These KWS models often struggle with confusing keywords, such as "blue" versus "glue". This paper introduces an effective way to augment the training with confusable utterances where keywords are generated and grouped from large language models (LLMs), and speech signals are synthesized with diverse speaking styles from text-to-speech (TTS) engines. To better measure user experience on confusable KWS, we define a new northstar metric using the average area under DET curve from confusable groups (c-AUC). Featuring high scalability and zero labor cost, the proposed method improves AUC by 3.7% and c-AUC by 11.3% on the Speech Commands testing set.

[Arxiv](https://arxiv.org/abs/2505.22995)