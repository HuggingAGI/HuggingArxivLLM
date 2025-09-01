# 检测AI代码生成器中的隐蔽数据投毒攻击

发布时间：2025年08月29日

`LLM应用` `基础理论`

> Detecting Stealthy Data Poisoning Attacks in AI Code Generators

# 摘要

> 自然语言到代码生成的深度学习（DL）模型如今已成为现代软件开发流程的核心组成部分。然而，这些模型严重依赖从非净化在线来源收集的海量数据，这使其极易遭受数据投毒攻击——攻击者通过注入恶意样本，以微妙方式扭曲模型行为。近期的定向攻击无需依赖显式触发器即可发起，它们会静默替换安全代码，用语义等效但存在漏洞的实现取而代之，这让检测方法极难分辨干净样本与投毒样本。针对这种隐蔽威胁模型，我们系统研究了现有投毒检测方法的有效性。具体来说，我们对三个深度学习模型（CodeBERT、CodeT5+、AST-T5）实施定向投毒，并评估了频谱特征分析、激活聚类和静态分析这三种防御手段的效果。研究结果显示，所有方法均难以检测无触发器投毒：基于表示的方法无法分离投毒样本，静态分析则存在误报与漏报，这凸显了为AI辅助代码生成构建更健壮、不依赖触发器的防御机制的迫切需求。

> Deep learning (DL) models for natural language-to-code generation have become integral to modern software development pipelines. However, their heavy reliance on large amounts of data, often collected from unsanitized online sources, exposes them to data poisoning attacks, where adversaries inject malicious samples to subtly bias model behavior. Recent targeted attacks silently replace secure code with semantically equivalent but vulnerable implementations without relying on explicit triggers to launch the attack, making it especially hard for detection methods to distinguish clean from poisoned samples. We present a systematic study on the effectiveness of existing poisoning detection methods under this stealthy threat model. Specifically, we perform targeted poisoning on three DL models (CodeBERT, CodeT5+, AST-T5), and evaluate spectral signatures analysis, activation clustering, and static analysis as defenses. Our results show that all methods struggle to detect triggerless poisoning, with representation-based approaches failing to isolate poisoned samples and static analysis suffering false positives and false negatives, highlighting the need for more robust, trigger-independent defenses for AI-assisted code generation.

[Arxiv](https://arxiv.org/abs/2508.21636)