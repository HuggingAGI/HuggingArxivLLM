# 大型语言模型的自适应PII缓解框架

发布时间：2025年01月21日

`LLM应用

理由：该论文主要讨论的是如何通过自适应系统来降低大型语言模型（LLMs）中个人身份信息（PII）和敏感个人信息（SPI）的风险，并确保其符合全球数据保护法律的要求。这涉及到LLMs在实际应用中的合规性和隐私保护问题，属于LLM在实际应用场景中的具体应用和优化，因此归类为LLM应用。` `数据保护` `隐私合规`

> Adaptive PII Mitigation Framework for Large Language Models

# 摘要

> 人工智能（AI）正面临全球数据保护法律和执法实践带来的日益严峻的挑战。GDPR和CCPA等法规对机器学习（ML）模型提出了严格的合规要求，尤其是在个人数据使用方面。这些法律赋予个人数据更正和删除等权利，使得依赖大规模数据集的大型语言模型（LLMs）的训练和部署变得更加复杂。公共数据的可用性并不等同于其在ML中的合法使用，这进一步加剧了挑战。
    本文提出了一种自适应系统，旨在降低LLMs中个人身份信息（PII）和敏感个人信息（SPI）的风险。该系统能够动态适应多种监管框架，并无缝集成到治理、风险和合规（GRC）系统中。通过先进的自然语言处理（NLP）技术、上下文感知分析和策略驱动的数据掩码，该系统确保了监管合规性。
    基准测试显示，该系统在护照号码识别上的F1得分为0.95，远超Microsoft Presidio（0.33）和Amazon Comprehend（0.54）。在用户评估中，该系统获得了4.6/5的平均信任评分，用户对其准确性和透明度给予了高度评价。观察发现，相较于允许假名化和用户选择退出的CCPA，GDPR下的匿名化要求更为严格。这些结果证明了该系统作为企业隐私合规的可扩展和稳健解决方案的有效性。

> Artificial Intelligence (AI) faces growing challenges from evolving data protection laws and enforcement practices worldwide. Regulations like GDPR and CCPA impose strict compliance requirements on Machine Learning (ML) models, especially concerning personal data use. These laws grant individuals rights such as data correction and deletion, complicating the training and deployment of Large Language Models (LLMs) that rely on extensive datasets. Public data availability does not guarantee its lawful use for ML, amplifying these challenges.
  This paper introduces an adaptive system for mitigating risk of Personally Identifiable Information (PII) and Sensitive Personal Information (SPI) in LLMs. It dynamically aligns with diverse regulatory frameworks and integrates seamlessly into Governance, Risk, and Compliance (GRC) systems. The system uses advanced NLP techniques, context-aware analysis, and policy-driven masking to ensure regulatory compliance.
  Benchmarks highlight the system's effectiveness, with an F1 score of 0.95 for Passport Numbers, outperforming tools like Microsoft Presidio (0.33) and Amazon Comprehend (0.54). In human evaluations, the system achieved an average user trust score of 4.6/5, with participants acknowledging its accuracy and transparency. Observations demonstrate stricter anonymization under GDPR compared to CCPA, which permits pseudonymization and user opt-outs. These results validate the system as a scalable and robust solution for enterprise privacy compliance.

[Arxiv](https://arxiv.org/abs/2501.12465)