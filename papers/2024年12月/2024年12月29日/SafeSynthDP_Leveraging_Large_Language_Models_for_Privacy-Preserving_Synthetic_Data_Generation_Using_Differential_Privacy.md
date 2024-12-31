# SafeSynthDP：借助大型语言模型，运用差分隐私实现隐私保护的合成数据生成

发布时间：2024年12月29日

`LLM应用` `机器学习` `隐私保护`

> SafeSynthDP: Leveraging Large Language Models for Privacy-Preserving Synthetic Data Generation Using Differential Privacy

# 摘要

> 机器学习（ML）模型往往依赖可能涵盖敏感或个人信息的训练数据，这引发了严重的隐私忧虑。像《通用数据保护条例》（GDPR）和《加州消费者隐私法案》（CCPA）之类的立法框架，促使我们去开发既能保护隐私又能维持数据实用性的策略。在本文中，我们探究大型语言模型（LLMs）生成融合差分隐私（DP）机制的合成数据集的能力，以此在不直接暴露敏感信息的情况下开展数据驱动的研究和模型训练。我们的方法把基于DP的噪声注入方式，比如拉普拉斯分布和高斯分布，融入到数据生成流程中。接着，我们通过对比在这些DP强化的合成数据集上训练的ML模型和在原始数据上训练的模型的表现，来评估这些数据集的实用性。为了证实隐私保障，我们评估生成的合成数据对成员推理攻击及相关威胁的抵御能力。实验结果显示，在LLM驱动的合成数据生成中融入DP，在隐私保护和数据实用性之间达成了可行的平衡。本研究为LLMs的隐私保护能力提供了基础方法和见解，为合规且有效的ML研究和应用铺平了道路。

> Machine learning (ML) models frequently rely on training data that may include sensitive or personal information, raising substantial privacy concerns. Legislative frameworks such as the General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA) have necessitated the development of strategies that preserve privacy while maintaining the utility of data. In this paper, we investigate the capability of Large Language Models (LLMs) to generate synthetic datasets integrated with Differential Privacy (DP) mechanisms, thereby enabling data-driven research and model training without direct exposure of sensitive information. Our approach incorporates DP-based noise injection methods, including Laplace and Gaussian distributions, into the data generation process. We then evaluate the utility of these DP-enhanced synthetic datasets by comparing the performance of ML models trained on them against models trained on the original data. To substantiate privacy guarantees, we assess the resilience of the generated synthetic data to membership inference attacks and related threats. The experimental results demonstrate that integrating DP within LLM-driven synthetic data generation offers a viable balance between privacy protection and data utility. This study provides a foundational methodology and insight into the privacy-preserving capabilities of LLMs, paving the way for compliant and effective ML research and applications.

[Arxiv](https://arxiv.org/abs/2412.20641)