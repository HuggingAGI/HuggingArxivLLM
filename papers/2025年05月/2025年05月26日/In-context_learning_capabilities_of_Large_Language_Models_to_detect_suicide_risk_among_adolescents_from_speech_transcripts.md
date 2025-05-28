# 大语言模型通过语音记录检测青少年自杀风险的上下文学习能力

发布时间：2025年05月26日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在自杀风险评估中的应用，具体是通过文本转录分类来实现的。研究中使用了系统性提示工程和in-context学习方法，属于将LLMs应用于实际问题的范畴。因此，这篇论文属于LLM应用类别。` `心理健康`

> In-context learning capabilities of Large Language Models to detect suicide risk among adolescents from speech transcripts

# 摘要

> 青少年早期自杀风险检测至关重要，但目前的评估方法在可扩展性方面面临挑战。本文介绍了我们对首届SpeechWellness挑战赛（SW1）的参赛方案，该比赛旨在通过语音分析评估中国青少年的自杀风险。由于语音匿名化限制，我们专注于语言特征，利用大型语言模型（LLMs）进行文本转录分类。通过DSPy进行系统性提示工程，我们开发了一种强大的in-context学习方法，在语言和声学标记上均优于传统的微调方法。我们的系统在180多个参赛方案中排名第三和第四，仅使用转录文本实现了0.68的准确率（F1=0.7）。消融分析表明，增加提示示例可提升性能（p=0.003），但不同模型类型和大小的影响程度各不相同。这些发现推动了自杀风险评估的自动化，并证明了LLMs在心理健康应用中的价值。

> Early suicide risk detection in adolescents is critical yet hindered by scalability challenges of current assessments. This paper presents our approach to the first SpeechWellness Challenge (SW1), which aims to assess suicide risk in Chinese adolescents through speech analysis. Due to speech anonymization constraints, we focused on linguistic features, leveraging Large Language Models (LLMs) for transcript-based classification. Using DSPy for systematic prompt engineering, we developed a robust in-context learning approach that outperformed traditional fine-tuning on both linguistic and acoustic markers. Our systems achieved third and fourth places among 180+ submissions, with 0.68 accuracy (F1=0.7) using only transcripts. Ablation analyses showed that increasing prompt example improved performance (p=0.003), with varying effects across model types and sizes. These findings advance automated suicide risk assessment and demonstrate LLMs' value in mental health applications.

[Arxiv](https://arxiv.org/abs/2505.20491)