# 多语言音频中自发与脚本语音的分类

发布时间：2024年12月16日

`其他

理由：这篇论文主要讨论的是语音处理领域的一个具体问题，即如何区分脚本化语音和自发语音，并探讨了不同模型在这一任务上的表现。虽然提到了使用先进的音频变换器模型，但整体内容并不直接涉及大型语言模型（LLM）、检索增强生成（RAG）、智能体（Agent）或LLM的理论研究。因此，将其分类为“其他”更为合适。` `语音处理` `媒体推荐`

> Classification of Spontaneous and Scripted Speech for Multilingual Audio

# 摘要

> 区分脚本化语音和自发语音是理解语音风格对语音处理研究影响的关键工具，同时也能通过优化大型录音语音目录的分割，提升推荐系统和媒体用户的发现体验。本文探讨了构建一个跨格式和语言泛化能力强的分类器的挑战。我们系统评估了从传统手工特征到先进音频变换器的多种模型，并利用一个大型多语言专有播客数据集进行训练和验证。我们分析了每个模型在11种语言组中的表现，以评估跨语言偏见。实验还扩展到公开数据集，评估模型在非播客领域的泛化能力。结果表明，基于变换器的模型在区分脚本化和自发语音方面表现优异，超越了传统特征技术，达到了最先进的性能。

> Distinguishing scripted from spontaneous speech is an essential tool for better understanding how speech styles influence speech processing research. It can also improve recommendation systems and discovery experiences for media users through better segmentation of large recorded speech catalogues. This paper addresses the challenge of building a classifier that generalises well across different formats and languages. We systematically evaluate models ranging from traditional, handcrafted acoustic and prosodic features to advanced audio transformers, utilising a large, multilingual proprietary podcast dataset for training and validation. We break down the performance of each model across 11 language groups to evaluate cross-lingual biases. Our experimental analysis extends to publicly available datasets to assess the models' generalisability to non-podcast domains. Our results indicate that transformer-based models consistently outperform traditional feature-based techniques, achieving state-of-the-art performance in distinguishing between scripted and spontaneous speech across various languages.

[Arxiv](https://arxiv.org/abs/2412.11896)