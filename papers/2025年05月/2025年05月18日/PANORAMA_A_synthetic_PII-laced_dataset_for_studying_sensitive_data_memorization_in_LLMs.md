# PANORAMA：一个合成PII掺杂数据集，用于研究LLM中的敏感数据记忆现象

发布时间：2025年05月18日

`LLM应用

理由：这篇论文专注于大型语言模型在处理敏感和个人可识别信息（PII）时的隐私风险，以及如何通过构建合成语料库来研究和缓解这些问题。它探讨了模型记忆敏感数据的情况，并提出了一个实际的数据集用于隐私风险评估和模型审核，属于LLM的实际应用范畴。` `数据隐私保护` `模型审核`

> PANORAMA: A synthetic PII-laced dataset for studying sensitive data memorization in LLMs

# 摘要

> 大型语言模型（LLMs）对敏感和个人可识别信息（PII）的记忆随着模型规模的不断扩大和在实际应用场景中的广泛应用，带来了日益严重的隐私风险。目前，由于缺乏能够全面反映网络上敏感信息多样性、真实且符合伦理来源的数据集，研究敏感和PII数据记忆以及开发缓解策略的努力受到了阻碍。我们引入了PANORAMA——基于个人资料的自然在线表示和属性记忆分析的合成语料库，该语料库包含384,789个样本，源自9,674个合成个人资料，旨在紧密模拟PII和敏感数据在自然在线环境中出现的分布、多样性和上下文。我们的数据生成流水线从使用受限选择构建内部一致、多属性的人类个人资料开始，以反映现实世界的人口统计学特征，如教育、健康属性、财务状况等。通过结合零样本提示和OpenAI o3-mini，我们生成了多种多样的内容类型——包括维基百科风格的文章、社交媒体帖子、论坛讨论、在线评论、评论和市场列表——每种内容都嵌入了现实且上下文合适的PII和其他敏感信息。通过使用1x、5x、10x和25x数据复制率对Mistral-7B模型进行微调，并测量PII记忆率，我们验证了PANORAMA的实用性——不仅揭示了记忆率随着重复次数的增加而持续增长，还显示了不同内容类型之间的差异，突显了PANORAMA在模拟记忆风险如何因上下文而异的能力。我们的数据集和代码公开可用，为隐私风险评估、模型审核以及开发隐私保护的LLMs提供了急需的资源。

> The memorization of sensitive and personally identifiable information (PII) by large language models (LLMs) poses growing privacy risks as models scale and are increasingly deployed in real-world applications. Existing efforts to study sensitive and PII data memorization and develop mitigation strategies are hampered by the absence of comprehensive, realistic, and ethically sourced datasets reflecting the diversity of sensitive information found on the web. We introduce PANORAMA - Profile-based Assemblage for Naturalistic Online Representation and Attribute Memorization Analysis, a large-scale synthetic corpus of 384,789 samples derived from 9,674 synthetic profiles designed to closely emulate the distribution, variety, and context of PII and sensitive data as it naturally occurs in online environments. Our data generation pipeline begins with the construction of internally consistent, multi-attribute human profiles using constrained selection to reflect real-world demographics such as education, health attributes, financial status, etc. Using a combination of zero-shot prompting and OpenAI o3-mini, we generate diverse content types - including wiki-style articles, social media posts, forum discussions, online reviews, comments, and marketplace listings - each embedding realistic, contextually appropriate PII and other sensitive information. We validate the utility of PANORAMA by fine-tuning the Mistral-7B model on 1x, 5x, 10x, and 25x data replication rates with a subset of data and measure PII memorization rates - revealing not only consistent increases with repetition but also variation across content types, highlighting PANORAMA's ability to model how memorization risks differ by context. Our dataset and code are publicly available, providing a much-needed resource for privacy risk assessment, model auditing, and the development of privacy-preserving LLMs.

[Arxiv](https://arxiv.org/abs/2505.12238)