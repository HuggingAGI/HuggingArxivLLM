# 是知识数据库还是毒库？通过 LLM 激活来检测 RAG 中毒攻击

发布时间：2024年11月28日

`RAG` `语言模型` `信息安全`

> Knowledge Database or Poison Base? Detecting RAG Poisoning Attack through LLM Activations

# 摘要

> 随着大型语言模型（LLMs）在各个领域和实际应用中逐步铺开，保障 LLMs 的安全性和稳定性愈发重要。检索增强生成（RAG）是一种前沿手段，旨在化解大型语言模型（LLMs）的局限。通过从相关知识数据库中检索信息，RAG 充实了 LLMs 的输入，让其能生成更精准、更贴合语境的回应。需要注意的是，知识数据库源自像维基百科这样的公开渠道，不可避免地带来了新的攻击面。RAG 中毒指的是向知识数据库注入恶意文本，最终致使生成攻击者的目标回应（也称中毒回应）。然而，当下检测这类中毒攻击的有效方法有限。我们意在这项工作中填补这一空缺。具体而言，我们引入了 RevPRAG，这是一个灵活且自动化的检测通道，借助 LLMs 的激活来检测中毒回应。我们的调研揭示了 LLMs 在生成正确回应和中毒回应时激活的不同模式。我们在多个基准数据集和 RAG 架构上的成果显示，我们的方法能达到 98%的真阳性率，同时将假阳性率维持在接近 1%的水平。我们还评估了专门为 LLMs 设计、适用于识别 RAG 中毒回应的最新后门检测方法。结果表明，我们的方法大幅超越了它们。

> As Large Language Models (LLMs) are progressively deployed across diverse fields and real-world applications, ensuring the security and robustness of LLMs has become ever more critical. Retrieval-Augmented Generation (RAG) is a cutting-edge approach designed to address the limitations of large language models (LLMs). By retrieving information from the relevant knowledge database, RAG enriches the input to LLMs, enabling them to produce responses that are more accurate and contextually appropriate. It is worth noting that the knowledge database, being sourced from publicly available channels such as Wikipedia, inevitably introduces a new attack surface. RAG poisoning involves injecting malicious texts into the knowledge database, ultimately leading to the generation of the attacker's target response (also called poisoned response). However, there are currently limited methods available for detecting such poisoning attacks. We aim to bridge the gap in this work. Particularly, we introduce RevPRAG, a flexible and automated detection pipeline that leverages the activations of LLMs for poisoned response detection. Our investigation uncovers distinct patterns in LLMs' activations when generating correct responses versus poisoned responses. Our results on multiple benchmark datasets and RAG architectures show our approach could achieve 98% true positive rate, while maintaining false positive rates close to 1%. We also evaluate recent backdoor detection methods specifically designed for LLMs and applicable for identifying poisoned responses in RAG. The results demonstrate that our approach significantly surpasses them.

[Arxiv](https://arxiv.org/abs/2411.18948)