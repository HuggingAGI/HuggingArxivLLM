# 自监督学习中的语言偏见对自动语音识别的影响

发布时间：2025年01月31日

`LLM理论

理由：这篇论文主要探讨了自监督学习（SSL）在多语言自动语音识别（ASR）模型中的应用，特别是XLS-R模型中的语言偏见问题。虽然SSL和ASR模型本身并不直接涉及大型语言模型（LLM），但论文中提到的“彩票假设”（LTH）和模型权重的研究与LLM的理论研究有相似之处，尤其是在模型训练和微调过程中如何选择和利用特定子网络的问题。因此，这篇论文更适合归类为“LLM理论”，因为它涉及了模型训练和优化的理论基础，而不是具体的应用或代理（Agent）技术。` `语音识别` `多语言处理`

> Language Bias in Self-Supervised Learning For Automatic Speech Recognition

# 摘要

> 自监督学习（SSL）在深度学习中用于训练大型数据集，无需昂贵的数据标注。最近，XLS-R等大型自动语音识别（ASR）模型利用SSL同时训练了上百种语言。然而，深入研究发现，XLS-R的大部分训练数据来自少数几种语言。尽管SSL在多个领域中被证明存在偏见，但多语言SSL ASR中的语言偏见尚未得到充分研究。本文利用彩票假设（LTH）识别XLS-R中的语言特定子网络，并测试其在多种语言上的性能。结果表明，在微调时，XLS-R绕过了传统语言学知识，仅依赖对预训练数据贡献最大的语言的权重进行构建。

> Self-supervised learning (SSL) is used in deep learning to train on large datasets without the need for expensive labelling of the data. Recently, large Automatic Speech Recognition (ASR) models such as XLS-R have utilised SSL to train on over one hundred different languages simultaneously. However, deeper investigation shows that the bulk of the training data for XLS-R comes from a small number of languages. Biases learned through SSL have been shown to exist in multiple domains, but language bias in multilingual SSL ASR has not been thoroughly examined. In this paper, we utilise the Lottery Ticket Hypothesis (LTH) to identify language-specific subnetworks within XLS-R and test the performance of these subnetworks on a variety of different languages. We are able to show that when fine-tuning, XLS-R bypasses traditional linguistic knowledge and builds only on weights learned from the languages with the largest data contribution to the pretraining data.

[Arxiv](https://arxiv.org/abs/2501.19321)