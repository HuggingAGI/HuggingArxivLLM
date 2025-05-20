# # PANORAMA：用于研究大型语言模型敏感数据记忆的合成数据集

PANORAMA 是一个特别设计的合成数据集，用于深入研究大型语言模型（LLMs）在处理个人身份信息（PII）时的敏感数据记忆特性。该数据集旨在帮助研究人员揭示 LLMs 在训练和推理过程中对敏感信息的存储与泄露机制，从而为提升模型的安全性和隐私保护提供重要参考。

发布时间：2025年05月18日

`LLM应用` `隐私保护` `数据隐私`

> PANORAMA: A synthetic PII-laced dataset for studying sensitive data memorization in LLMs

# 摘要

> 大型语言模型（LLMs）在记忆敏感信息和个人身份识别信息（PII）方面带来的隐私风险随着模型规模的扩大和在现实世界应用中的广泛应用而日益严重。现有的研究努力受到限制，因为缺乏全面、真实且来源符合伦理的代表性数据集，这些数据集能够反映网络上存在的敏感信息的多样性。我们引入了PANORAMA——一种基于个人资料的自然在线表示和属性记忆分析的合成语料库，包含384,789个样本，这些样本来源于9,674个经过精心设计的合成个人资料，旨在精确模拟PII和敏感数据在自然在线环境中的分布、多样性和上下文。我们的数据生成管道始于使用受限选择构建内部一致的多属性人类个人资料，以反映现实世界的人口统计学特征，如教育、健康属性、财务状况等。通过结合零样本提示和OpenAI o3-mini，我们生成了多种多样的内容类型——包括维基百科风格的文章、社交媒体帖子、论坛讨论、在线评论、评论和市场列表——每种内容都嵌入了现实且上下文相关的PII和其他敏感信息。我们通过使用PANORAMA数据集的不同复制率（1x、5x、10x和25x）对Mistral-7B模型进行微调，并测量PII记忆率，验证了PANORAMA的实用性。结果不仅显示出重复次数增加时记忆率的一致上升，还揭示了不同内容类型之间的差异，突显了PANORAMA在模拟不同上下文中记忆风险差异的能力。我们的数据集和代码已公开发布，为隐私风险评估、模型审核以及开发隐私保护型LLMs提供了急需的资源。

> The memorization of sensitive and personally identifiable information (PII) by large language models (LLMs) poses growing privacy risks as models scale and are increasingly deployed in real-world applications. Existing efforts to study sensitive and PII data memorization and develop mitigation strategies are hampered by the absence of comprehensive, realistic, and ethically sourced datasets reflecting the diversity of sensitive information found on the web. We introduce PANORAMA - Profile-based Assemblage for Naturalistic Online Representation and Attribute Memorization Analysis, a large-scale synthetic corpus of 384,789 samples derived from 9,674 synthetic profiles designed to closely emulate the distribution, variety, and context of PII and sensitive data as it naturally occurs in online environments. Our data generation pipeline begins with the construction of internally consistent, multi-attribute human profiles using constrained selection to reflect real-world demographics such as education, health attributes, financial status, etc. Using a combination of zero-shot prompting and OpenAI o3-mini, we generate diverse content types - including wiki-style articles, social media posts, forum discussions, online reviews, comments, and marketplace listings - each embedding realistic, contextually appropriate PII and other sensitive information. We validate the utility of PANORAMA by fine-tuning the Mistral-7B model on 1x, 5x, 10x, and 25x data replication rates with a subset of data and measure PII memorization rates - revealing not only consistent increases with repetition but also variation across content types, highlighting PANORAMA's ability to model how memorization risks differ by context. Our dataset and code are publicly available, providing a much-needed resource for privacy risk assessment, model auditing, and the development of privacy-preserving LLMs.

[Arxiv](https://arxiv.org/abs/2505.12238)