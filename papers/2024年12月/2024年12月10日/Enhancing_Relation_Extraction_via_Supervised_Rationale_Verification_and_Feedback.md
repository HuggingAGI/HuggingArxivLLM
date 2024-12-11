# 借助有监督的原理验证与反馈提升关系抽取能力

发布时间：2024年12月10日

`LLM应用` `关系抽取` `语言模型`

> Enhancing Relation Extraction via Supervised Rationale Verification and Feedback

# 摘要

> 尽管现有的自动化反馈方法在纠正大型语言模型（LLMs）的输出上进展迅速，但因其特定的反馈目标和纠正方式，难以在关系抽取（RE）任务中良好应用。为解决此问题，我们提出了一个用于 RE 的全新自动化反馈框架，其中包含一个原理监督器，用于验证原理并提供重新选择的演示作为反馈以纠正初始预测。具体而言，我们首先设计了一种因果干预和观察方法，用于收集有偏/无偏的原理，以对原理监督器进行对比训练。接着，我们提出了一个验证 - 反馈 - 纠正流程，以迭代增强 LLMs 处理 RE 任务的能力。大量实验表明，我们所提出的框架显著优于现有方法。

> Despite the rapid progress that existing automated feedback methods have made in correcting the output of large language models (LLMs), these methods cannot be well applied to the relation extraction (RE) task due to their designated feedback objectives and correction manner. To address this problem, we propose a novel automated feedback framework for RE, which presents a rationale supervisor to verify the rationale and provide re-selected demonstrations as feedback to correct the initial prediction. Specifically, we first design a causal intervention and observation method for to collect biased/unbiased rationales for contrastive training the rationale supervisor. Then, we present a verification-feedback-correction procedure to iteratively enhance LLMs' capability of handling the RE task. Extensive experiments prove that our proposed framework significantly outperforms existing methods.

[Arxiv](https://arxiv.org/abs/2412.07289)