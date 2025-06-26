# KnowML：通过攻击知识图谱提升ML-NIDS的泛化能力

发布时间：2025年06月24日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来改进网络入侵检测系统（ML-NIDS）。通过将LLMs应用于攻击知识的自动化分析和知识图谱的构建，KnowML框架展示了LLMs在实际应用中的潜力，特别是在增强安全检测方面。因此，这篇论文属于LLM应用类别。` `网络安全` `知识图谱`

> KnowML: Improving Generalization of ML-NIDS with Attack Knowledge Graphs

# 摘要

> 尽管基于机器学习的网络入侵检测系统（ML-NIDS）的研究已取得诸多进展，但其在检测多样化攻击变种方面的能力仍充满不确定性。现有研究多依赖于同质化数据集，这种做法不仅人为夸大了性能指标，还可能带来虚假的安全感。设计能够有效应对多种攻击变种的系统仍然是一个重大挑战。当前，ML-NIDS的进步依然严重依赖于人类专业知识，这种依赖可能将系统设计者的主观判断嵌入模型，从而影响其在不同攻击类型上的泛化能力。

为填补这一空白，我们提出了KnowML——一个将攻击知识整合到ML-NIDS中的知识引导机器学习框架。KnowML通过大型语言模型（LLMs）对攻击实现进行自动化分析，系统性地探索威胁格局。它构建了一个统一的攻击策略知识图谱，并在此基础上应用符号推理生成增强输入，将领域知识直接融入ML-NIDS的设计过程。

我们在28种现实攻击变种上评估了KnowML的表现，其中有10种是为本研究新收集的。研究发现，基线ML-NIDS模型完全无法检测到几种攻击变种，F1得分低至0%。相比之下，我们的知识引导方法在保持低于0.1%的误报率的同时，实现了高达99%的F1得分。

> Despite extensive research on Machine Learning-based Network Intrusion Detection Systems (ML-NIDS), their capability to detect diverse attack variants remains uncertain. Prior studies have largely relied on homogeneous datasets, which artificially inflate performance scores and offer a false sense of security. Designing systems that can effectively detect a wide range of attack variants remains a significant challenge. The progress of ML-NIDS continues to depend heavily on human expertise, which can embed subjective judgments of system designers into the model, potentially hindering its ability to generalize across diverse attack types.
  To address this gap, we propose KnowML, a framework for knowledge-guided machine learning that integrates attack knowledge into ML-NIDS. KnowML systematically explores the threat landscape by leveraging Large Language Models (LLMs) to perform automated analysis of attack implementations. It constructs a unified Knowledge Graph (KG) of attack strategies, on which it applies symbolic reasoning to generate KG-Augmented Input, embedding domain knowledge directly into the design process of ML-NIDS.
  We evaluate KnowML on 28 realistic attack variants, of which 10 are newly collected for this study. Our findings reveal that baseline ML-NIDS models fail to detect several variants entirely, achieving F1 scores as low as 0 %. In contrast, our knowledge-guided approach achieves up to 99 % F1 score while maintaining a False Positive Rate below 0.1 %.

[Arxiv](https://arxiv.org/abs/2506.19802)