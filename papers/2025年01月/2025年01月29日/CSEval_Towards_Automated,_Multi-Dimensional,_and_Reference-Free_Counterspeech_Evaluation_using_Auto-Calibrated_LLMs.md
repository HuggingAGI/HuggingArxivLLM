# CSEval：基于自动校准LLMs的自动化、多维度、无参考反言论评估

发布时间：2025年01月29日

`LLM应用

**理由**：该论文主要讨论了利用大型语言模型（LLM）自动生成反言论，并提出了一个新的评估框架和自动校准思维链方法（ACE）来评估反言论的质量。这属于LLM在实际应用中的使用，特别是用于生成和评估反言论，因此分类为LLM应用。` `社交媒体`

> CSEval: Towards Automated, Multi-Dimensional, and Reference-Free Counterspeech Evaluation using Auto-Calibrated LLMs

# 摘要

> 反言论作为一种对抗网络仇恨言论的有效手段，正受到越来越多的关注，尤其是利用语言模型自动生成反言论的研究。然而，该领域缺乏标准化的评估流程和与人类判断一致的自动化评估指标。现有的自动评估方法主要依赖相似性指标，难以全面捕捉反言论质量的复杂特性，如上下文相关性、攻击性或论证连贯性。这导致了对人工评估的高度依赖。为解决这些问题，我们推出了CSEval，一个全新的数据集和框架，用于从四个维度评估反言论质量：上下文相关性、攻击性、论证连贯性和适宜性。此外，我们提出了ACE（Auto-Calibrated COT for Counterspeech Evaluation），一种基于提示的自动校准思维链方法，利用大型语言模型对反言论进行评分。实验表明，ACE在与人类判断的相关性上优于ROUGE、METEOR和BertScore等传统指标，标志着自动反言论评估的重大进步。

> Counterspeech has been popular as an effective approach to counter online hate speech, leading to increasing research interest in automated counterspeech generation using language models. However, this field lacks standardised evaluation protocols and robust automated evaluation metrics that align with human judgement. Current automatic evaluation methods, primarily based on similarity metrics, do not effectively capture the complex and independent attributes of counterspeech quality, such as contextual relevance, aggressiveness, or argumentative coherence. This has led to an increased dependency on labor-intensive human evaluations to assess automated counter-speech generation methods. To address these challenges, we introduce CSEval, a novel dataset and framework for evaluating counterspeech quality across four dimensions: contextual-relevance, aggressiveness, argument-coherence, and suitableness. Furthermore, we propose Auto-Calibrated COT for Counterspeech Evaluation (ACE), a prompt-based method with auto-calibrated chain-of-thoughts (CoT) for scoring counterspeech using large language models. Our experiments show that ACE outperforms traditional metrics like ROUGE, METEOR, and BertScore in correlating with human judgement, indicating a significant advancement in automated counterspeech evaluation.

[Arxiv](https://arxiv.org/abs/2501.17581)