# # 生成式AI中的隐私保护

发布时间：2025年04月12日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在实际应用中面临的隐私挑战，并提出了一种隐私保护的生成式AI应用，属于LLM的应用层面研究。` `生成式AI` `隐私保护`

> Privacy Preservation in Gen AI Applications

# 摘要

> 生成式人工智能和大型语言模型（LLMs）推动的自然语言处理（NLP）技术飞速发展，使机器能够像人类一样理解和生成语言，从而彻底改变了客户服务、医疗保健和金融等领域。然而，这些技术也带来了严峻的隐私挑战：在大型数据集上训练的LLMs可能无意中吸收并泄露用户互动中的个人身份信息（PII）。由于深度神经网络的复杂性，追踪或阻止这种信息泄露变得极为困难。本研究针对这一问题，通过数据提取、模型反转和成员推断等攻击手段，深入检测生成式AI的潜在弱点。在此基础上，我们开发了一种具有抗攻击能力的隐私保护生成式AI应用。该应用通过在处理LLMs之前识别、修改或删除PII，实现了隐私保护与功能的平衡。此外，本研究还评估了Microsoft Azure、Google Cloud和AWS等云平台提供的隐私工具，以确定它们在保护AI应用方面的有效性。最终，本研究为生成式AI系统构建了一个以数据安全和道德AI实施为核心的隐私框架，为这些技术的安全和负责任使用奠定了基础。

> The ability of machines to comprehend and produce language that is similar to that of humans has revolutionized sectors like customer service, healthcare, and finance thanks to the quick advances in Natural Language Processing (NLP), which are fueled by Generative Artificial Intelligence (AI) and Large Language Models (LLMs). However, because LLMs trained on large datasets may unintentionally absorb and reveal Personally Identifiable Information (PII) from user interactions, these capabilities also raise serious privacy concerns. Deep neural networks' intricacy makes it difficult to track down or stop the inadvertent storing and release of private information, which raises serious concerns about the privacy and security of AI-driven data. This study tackles these issues by detecting Generative AI weaknesses through attacks such as data extraction, model inversion, and membership inference. A privacy-preserving Generative AI application that is resistant to these assaults is then developed. It ensures privacy without sacrificing functionality by using methods to identify, alter, or remove PII before to dealing with LLMs. In order to determine how well cloud platforms like Microsoft Azure, Google Cloud, and AWS provide privacy tools for protecting AI applications, the study also examines these technologies. In the end, this study offers a fundamental privacy paradigm for generative AI systems, focusing on data security and moral AI implementation, and opening the door to a more secure and conscientious use of these tools.

[Arxiv](https://arxiv.org/abs/2504.09095)