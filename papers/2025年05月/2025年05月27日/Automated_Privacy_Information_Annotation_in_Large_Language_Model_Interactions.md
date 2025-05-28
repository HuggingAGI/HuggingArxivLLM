# # 大型语言模型交互中的自动化隐私标注

发布时间：2025年05月27日

`LLM应用` `隐私保护` `数据安全`

> Automated Privacy Information Annotation in Large Language Model Interactions

# 摘要

> 与大型语言模型（LLMs）交互的用户在使用真实标识时，往往不知不觉地面临泄露私人信息的风险。因此，自动通知用户其查询是否泄露隐私，以及哪些短语泄露了什么隐私信息，已成为一项实际需求。然而，现有的隐私检测方法是为不同的目标和应用场景设计的，通常是在匿名内容中标记个人身份信息（PII）。在本研究中，为了支持开发和评估可在本地用户设备上部署的LLM交互隐私检测模型，我们构建了一个大规模的多语言数据集，包含24.9万个用户查询和15.4万个标注的隐私短语。特别地，我们利用基于云的强大LLMs构建了一个自动化隐私标注管道，用于从对话数据集中自动提取隐私短语并标注泄露的信息。我们还设计了隐私泄露、提取的隐私短语和隐私信息三个层次的评估指标。此外，我们使用轻量级LLMs建立了基线方法，包括无需调优和基于调优的方法，并对它们的性能进行了全面评估。评估结果揭示了当前性能与实际LLM应用需求之间的差距，这激励了未来基于我们数据集的研究，以开发更有效的本地隐私检测方法。

> Users interacting with large language models (LLMs) under their real identifiers often unknowingly risk disclosing private information. Automatically notifying users whether their queries leak privacy and which phrases leak what private information has therefore become a practical need. Existing privacy detection methods, however, were designed for different objectives and application scenarios, typically tagging personally identifiable information (PII) in anonymous content. In this work, to support the development and evaluation of privacy detection models for LLM interactions that are deployable on local user devices, we construct a large-scale multilingual dataset with 249K user queries and 154K annotated privacy phrases. In particular, we build an automated privacy annotation pipeline with cloud-based strong LLMs to automatically extract privacy phrases from dialogue datasets and annotate leaked information. We also design evaluation metrics at the levels of privacy leakage, extracted privacy phrase, and privacy information. We further establish baseline methods using light-weight LLMs with both tuning-free and tuning-based methods, and report a comprehensive evaluation of their performance. Evaluation results reveal a gap between current performance and the requirements of real-world LLM applications, motivating future research into more effective local privacy detection methods grounded in our dataset.

[Arxiv](https://arxiv.org/abs/2505.20910)