# 基于选择性注意力的联邦学习：提升临床文本分类的隐私与效率

发布时间：2025年04月16日

`LLM应用`

> Selective Attention Federated Learning: Improving Privacy and Efficiency for Clinical Text Classification

# 摘要

> 联邦学习（FL）在训练大型语言模型（LLMs）时面临通信开销和模型隐私的挑战，特别是在医疗应用中。为解决这些问题，我们提出了一种新型方法——选择性注意力联邦学习（SAFL），该方法动态微调那些被识别为注意力关键的变换层。通过利用注意力模式来确定层的重要性，SAFL显著减少了通信带宽，并增强了对差分隐私的抗性。在i2b2临床概念提取和MIMIC-III出院摘要等临床NLP基准测试中，SAFL不仅与集中式模型保持竞争力，还大幅提高了通信效率和隐私保护能力。

> Federated Learning (FL) faces major challenges regarding communication overhead and model privacy when training large language models (LLMs), especially in healthcare applications. To address these, we introduce Selective Attention Federated Learning (SAFL), a novel approach that dynamically fine-tunes only those transformer layers identified as attention-critical. By employing attention patterns to determine layer importance, SAFL significantly reduces communication bandwidth and enhances differential privacy resilience. Evaluations on clinical NLP benchmarks (i2b2 Clinical Concept Extraction and MIMIC-III discharge summaries) demonstrate that SAFL achieves competitive performance with centralized models while substantially improving communication efficiency and privacy preservation.

[Arxiv](https://arxiv.org/abs/2504.11793)