# 微调检索增强的预训练语言模型，改进深度断言生成

发布时间：2025年02月21日

`LLM应用` `软件工程`

> Improving Deep Assertion Generation via Fine-Tuning Retrieval-Augmented Pre-trained Language Models

# 摘要

> 单元测试确保软件系统各个模块的正确性，是提升软件质量和可靠性的基石。为了减少手动编写单元测试的工作量，研究者提出了多种自动生成功能断言的技术，其中近期的集成方法被认为是 state-of-the-art。尽管这些方法展现出巨大潜力，但仍存在一些限制，如依赖词法匹配检索断言，以及用于断言生成的训练语料库有限。

本研究提出了一种新颖的基于检索增强的深度断言生成方法——RetriGen，结合混合检索器和预训练语言模型（PLM）生成器。针对特定测试用例，RetriGen 首先构建混合断言检索器，从外部代码库中寻找最相关的 Test-Assert Pair。检索过程通过基于 token 和基于嵌入的检索器分别评估词法和语义相似性。随后，RetriGen 将断言生成建模为序列到序列任务，设计 PLM 基础的生成器预测正确断言。我们通过大规模实验，将 RetriGen 与六种先进方法在两个数据集和两个指标下进行对比。结果显示，RetriGen 达到 57.66% 的准确率和 73.24% 的 CodeBLEU，分别较基线平均提升 50.66% 和 14.14%，表现显著优于现有方法。

> Unit testing validates the correctness of the units of the software system under test and serves as the cornerstone in improving software quality and reliability. To reduce manual efforts in writing unit tests, some techniques have been proposed to automatically generate test assertions, with recent integration-based approaches considered state-of-the-art. Despite being promising, such integration-based approaches face several limitations, including reliance on lexical matching for assertion retrieval and a limited training corpus for assertion generation.
  This paper proposes a novel retrieval-augmented deep assertion generation approach, namely RetriGen, based on a hybrid retriever and a pre-trained language model (PLM)-based generator. Given a focal-test, RetriGen first builds a hybrid assertion retriever to search for the most relevant Test-Assert Pair from external codebases. The retrieval process considers lexical similarity and semantical similarity via a token-based and an embedding-based retriever, respectively. RetriGen then treats assertion generation as a sequence-to-sequence task and designs a PLM-based assertion generator to predict a correct assertion. We conduct extensive experiments to evaluate RetriGen against six state-of-the-art approaches across two large-scale datasets and two metrics. The results demonstrate that RetriGen achieves 57.66% accuracy and 73.24% CodeBLEU, outperforming all baselines with average improvements of 50.66% and 14.14%, respectively.

[Arxiv](https://arxiv.org/abs/2502.16071)