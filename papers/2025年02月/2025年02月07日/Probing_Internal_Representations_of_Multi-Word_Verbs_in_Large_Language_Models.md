# 探究大型语言模型中多词动词的内部表征

发布时间：2025年02月07日

`LLM理论` `语言学`

> Probing Internal Representations of Multi-Word Verbs in Large Language Models

# 摘要

> 本研究深入探讨了基于Transformer的大型语言模型中动词-介词组合（多词动词）的内部表示，重点关注模型如何在不同神经网络层捕捉词汇与句法特性。基于BERT架构，我们对两类动词-介词结构进行了分层分析：如'give up'的短语动词和如'look at'的介词动词。通过在模型内部表示上训练探查分类器，我们分别在词和句子层面进行了分类任务。研究发现，模型的中间层表现出最佳的分类性能。为了进一步揭示这些区别的本质，我们采用广义辨别值（GDV）进行了数据可分性测试。尽管GDV结果显示两种动词类型间线性可分性较弱，探查分类器仍保持了高准确率，表明这些语言类别的表示可能以非线性方式编码。这一发现与先前研究一致，证实神经网络中的语言差异并非总是以线性可分形式编码。本研究从计算角度支持了基于使用的语言结构表示理论，揭示了神经网络架构与语言结构间的复杂交互关系。

> This study investigates the internal representations of verb-particle combinations, called multi-word verbs, within transformer-based large language models (LLMs), specifically examining how these models capture lexical and syntactic properties at different neural network layers. Using the BERT architecture, we analyze the representations of its layers for two different verb-particle constructions: phrasal verbs like 'give up' and prepositional verbs like 'look at'. Our methodology includes training probing classifiers on the internal representations to classify these categories at both word and sentence levels. The results indicate that the model's middle layers achieve the highest classification accuracies. To further analyze the nature of these distinctions, we conduct a data separability test using the Generalized Discrimination Value (GDV). While GDV results show weak linear separability between the two verb types, probing classifiers still achieve high accuracy, suggesting that representations of these linguistic categories may be non-linearly separable. This aligns with previous research indicating that linguistic distinctions in neural networks are not always encoded in a linearly separable manner. These findings computationally support usage-based claims on the representation of verb-particle constructions and highlight the complex interaction between neural network architectures and linguistic structures.

[Arxiv](https://arxiv.org/abs/2502.04789)