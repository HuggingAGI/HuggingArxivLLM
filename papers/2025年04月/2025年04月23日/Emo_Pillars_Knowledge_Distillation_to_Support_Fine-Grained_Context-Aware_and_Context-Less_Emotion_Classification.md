# 情绪支柱：通过知识蒸馏实现细粒度上下文感知与无上下文情绪分类

发布时间：2025年04月23日

`LLM应用` `情感分析` `情绪分类`

> Emo Pillars: Knowledge Distillation to Support Fine-Grained Context-Aware and Context-Less Emotion Classification

# 摘要

> 大多数情感分析数据集缺乏表达意见的上下文，而这对于情绪理解至关重要。这些数据集还主要受限于几种情绪类别。像 GPT-4 这样的基础大型语言模型（LLMs）在情感预测上存在过度预测的问题，同时资源消耗也过高。我们设计了一个基于 LLM 的数据合成管道，并利用 Mistral-7b 这个大型模型，为轻量级的 BERT 类型编码器模型生成训练示例。我们专注于扩大示例的语义多样性，并提出将生成过程植根于叙事语料库中，以生成 28 种情绪类别下不重复且以故事情节为中心的具有独特上下文的表达。通过在 450 个 GPU 小时内进行 70 万次推理，我们贡献了一个包含 10 万条上下文和 30 万条无上下文示例的数据集，以覆盖两种场景。我们使用它来微调预训练的编码器，从而得到多个情绪支柱模型。我们展示了情绪支柱模型在特定任务（如 GoEmotions、ISEAR、IEMOCAP 和 EmoContext）上经过调整后，能够很好地适应新领域，并在前三个数据集上达到 SOTA 性能。我们还对数据集进行了验证，进行了统计分析和人工评估，确认了我们在表达多样化（尽管中性类别效果稍逊）和上下文个性化方面的成功，同时指出了需要改进管道中对 taxonomy 外标签处理的需求。

> Most datasets for sentiment analysis lack context in which an opinion was expressed, often crucial for emotion understanding, and are mainly limited by a few emotion categories. Foundation large language models (LLMs) like GPT-4 suffer from over-predicting emotions and are too resource-intensive. We design an LLM-based data synthesis pipeline and leverage a large model, Mistral-7b, for the generation of training examples for more accessible, lightweight BERT-type encoder models. We focus on enlarging the semantic diversity of examples and propose grounding the generation into a corpus of narratives to produce non-repetitive story-character-centered utterances with unique contexts over 28 emotion classes. By running 700K inferences in 450 GPU hours, we contribute with the dataset of 100K contextual and also 300K context-less examples to cover both scenarios. We use it for fine-tuning pre-trained encoders, which results in several Emo Pillars models. We show that Emo Pillars models are highly adaptive to new domains when tuned to specific tasks such as GoEmotions, ISEAR, IEMOCAP, and EmoContext, reaching the SOTA performance on the first three. We also validate our dataset, conducting statistical analysis and human evaluation, and confirm the success of our measures in utterance diversification (although less for the neutral class) and context personalization, while pointing out the need for improved handling of out-of-taxonomy labels within the pipeline.

[Arxiv](https://arxiv.org/abs/2504.16856)