# RN-F: 缓解大型语言模型污染数据的创新方法

发布时间：2025年05月19日

`LLM理论` `科学研究` `企业自动化`

> RN-F: A Novel Approach for Mitigating Contaminated Data in Large Language Models

# 摘要

> 大型语言模型（LLMs）已成为现代人工智能的基石，驱动着从代码生成、虚拟助手到科学研究和企业自动化的广泛应用。然而，关于数据污染——即测试数据与训练数据重叠——的担忧，引发了对这些应用可靠性的严重质疑。尽管人们意识到这一问题，但现有方法在有效识别或缓解污染方面仍显不足。本文中，我们提出了一种名为残差噪声指纹（RN-F）的新型框架，用于检测 LLM 中的污染数据。RN-F 是一种单次遍历、无需梯度的检测方法，利用残差信号模式，而无需引入额外的浮点运算。我们的方法轻量、模型无关且高效。我们在多种 LLM 上对 RN-F 进行了测试，并在多个污染数据集上进行了评估，结果表明 RN-F 一致优于现有的最先进方法，在污染检测指标上实现了高达 10.5% 的性能提升。

> Large Language Models (LLMs) have become foundational in modern artificial intelligence, powering a wide range of applications from code generation and virtual assistants to scientific research and enterprise automation. However, concerns about data contamination--where test data overlaps with training data--have raised serious questions about the reliability of these applications. Despite awareness of this issue, existing methods fall short in effectively identifying or mitigating contamination. In this paper, we propose Residual-Noise Fingerprinting (RN-F), a novel framework for detecting contaminated data in LLMs. RN-F is a single-pass, gradient-free detection method that leverages residual signal patterns without introducing additional floating-point operations. Our approach is lightweight, model-agnostic, and efficient. We evaluate RN-F on multiple LLMs across various contaminated datasets and show that it consistently outperforms existing state-of-the-art methods, achieving performance improvements of up to 10.5% in contamination detection metrics.

[Arxiv](https://arxiv.org/abs/2505.13249)