# 架起桥梁：一种提升音素转换效果并降低成本的中间语言，解决多音字的歧义

发布时间：2025年05月10日

`LLM应用` `语音技术`

> Bridging the Gap: An Intermediate Language for Enhanced and Cost-Effective Grapheme-to-Phoneme Conversion with Homographs with Multiple Pronunciations Disambiguation

# 摘要

> 波斯语的字母到音素（G2P）转换面临独特的挑战，尤其是其复杂的语音学特征，如同形异义词和Ezafe，在正式和非正式语言环境中普遍存在。本文提出了一种专为波斯语处理设计的中间语言，通过多方面的综合方法有效应对这些挑战。我们的方法结合了大型语言模型（LLM）提示技术和专门的序列到序列机器转写架构。我们开发了一种系统化的方法，用于构建全面的词汇数据库，解决具有多种发音的同形异义词（多音词）的歧义问题，并通过形式概念分析实现语义区分。我们使用两个数据集对模型进行训练：用于正式和非正式波斯语的LLM生成数据集，以及用于非正式语言变体的B-Plus播客数据集。实验结果表明，与现有最先进方法相比，我们的模型在处理波斯语音素转换复杂性方面表现更优。我们的模型显著提升了音素错误率（PER）指标，为波斯语G2P转换的准确性树立了新的基准。这项研究为低资源语言处理领域提供了重要贡献，并为波斯语文本到语音系统提供了一个强大的解决方案，同时也展示了其在波斯语之外的应用潜力。具体而言，该方法可以扩展到具有丰富同形异义现象的语言，如中文和阿拉伯语。


> Grapheme-to-phoneme (G2P) conversion for Persian presents unique challenges due to its complex phonological features, particularly homographs and Ezafe, which exist in formal and informal language contexts. This paper introduces an intermediate language specifically designed for Persian language processing that addresses these challenges through a multi-faceted approach. Our methodology combines two key components: Large Language Model (LLM) prompting techniques and a specialized sequence-to-sequence machine transliteration architecture. We developed and implemented a systematic approach for constructing a comprehensive lexical database for homographs with multiple pronunciations disambiguation often termed polyphones, utilizing formal concept analysis for semantic differentiation. We train our model using two distinct datasets: the LLM-generated dataset for formal and informal Persian and the B-Plus podcasts for informal language variants. The experimental results demonstrate superior performance compared to existing state-of-the-art approaches, particularly in handling the complexities of Persian phoneme conversion. Our model significantly improves Phoneme Error Rate (PER) metrics, establishing a new benchmark for Persian G2P conversion accuracy. This work contributes to the growing research in low-resource language processing and provides a robust solution for Persian text-to-speech systems and demonstrating its applicability beyond Persian. Specifically, the approach can extend to languages with rich homographic phenomena such as Chinese and Arabic

[Arxiv](https://arxiv.org/abs/2505.06599)