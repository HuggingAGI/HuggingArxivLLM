# PrivacyXray：基于语义一致性和概率确定性检测 LLMs 中的隐私泄露

发布时间：2025年06月24日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在隐私泄露检测中的应用，提出了PrivacyXray框架，用于分析LLM内部状态以检测隐私泄露。研究集中在如何利用LLMs进行隐私保护，属于应用层面的创新。` `隐私保护` `人工智能`

> PrivacyXray: Detecting Privacy Breaches in LLMs through Semantic Consistency and Probability Certainty

# 摘要

> 大型语言模型（LLMs）在医疗、金融和法律服务等敏感领域的广泛应用引发了人们对隐私泄露的担忧。尽管越狱攻击等隐私提取攻击能迫使模型泄露敏感信息，但现有方法无法验证提取信息的准确性，主要原因在于缺乏公开数据集用于交叉验证，导致推理过程中的隐私检测存在重大缺口。

为解决这一问题，我们提出了PrivacyXray——一个基于分析LLM内部状态的全新隐私泄露检测框架。研究发现，当生成正确的隐私信息时，LLMs会表现出更高的语义连贯性和概率确定性。基于这一发现，PrivacyXray采用四重检测指标：层内语义相似度、层间语义相似度，以及词级别和句子级别的概率分布。

PrivacyXray通过合成现实隐私数据和基于LLM内部状态的检测机制，成功克服了开源隐私数据集缺乏以及对外部数据验证依赖的难题。实验结果表明，PrivacyXray在五个主流LLMs上实现了稳定且一致的性能表现，平均准确率达到92.69%。与现有最优方法相比，PrivacyXray的平均准确率提升了20.06%，充分证明了其在实际应用中的稳定性和实用价值。


> Large Language Models (LLMs) are widely used in sensitive domains, including healthcare, finance, and legal services, raising concerns about potential private information leaks during inference. Privacy extraction attacks, such as jailbreaking, expose vulnerabilities in LLMs by crafting inputs that force the models to output sensitive information. However, these attacks cannot verify whether the extracted private information is accurate, as no public datasets exist for cross-validation, leaving a critical gap in private information detection during inference. To address this, we propose PrivacyXray, a novel framework detecting privacy breaches by analyzing LLM inner states. Our analysis reveals that LLMs exhibit higher semantic coherence and probabilistic certainty when generating correct private outputs. Based on this, PrivacyXray detects privacy breaches using four metrics: intra-layer and inter-layer semantic similarity, token-level and sentence-level probability distributions. PrivacyXray addresses critical challenges in private information detection by overcoming the lack of open-source private datasets and eliminating reliance on external data for validation. It achieves this through the synthesis of realistic private data and a detection mechanism based on the inner states of LLMs. Experiments show that PrivacyXray achieves consistent performance, with an average accuracy of 92.69% across five LLMs. Compared to state-of-the-art methods, PrivacyXray achieves significant improvements, with an average accuracy increase of 20.06%, highlighting its stability and practical utility in real-world applications.

[Arxiv](https://arxiv.org/abs/2506.19563)