# 打造更安全的聊天机器人：自定义GPTs政策合规性评估框架

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论的是如何通过一个可扩展的框架来评估定制GPT是否符合OpenAI的使用政策，涉及到的技术包括自动数据收集、红队提示生成器以及利用LLM作为法官来分析政策违规。这些内容都属于LLM在实际应用中的具体问题，特别是如何确保LLM在定制化应用中的安全性和合规性。因此，这篇论文应被分类为LLM应用。` `人工智能` `合规管理`

> Towards Safer Chatbots: A Framework for Policy Compliance Evaluation of Custom GPTs

# 摘要

> 大型语言模型（LLMs）如今在各个领域大放异彩，深入社会各个角落。通过对通用LLMs（如GPT）进行任务微调，定制GPT如雨后春笋般涌现，并通过OpenAI的GPT商店等平台广泛流通。然而，这些模型的“黑箱”特性带来了显著的安全和合规风险。为此，我们提出了一种可扩展的框架，用于自动评估定制GPT是否符合OpenAI的使用政策。该框架包含三大核心模块：（1）从GPT商店自动发现并收集模型数据，（2）针对特定政策类别和目标GPT特性定制的红队提示生成器，以及（3）利用LLM作为法官的技术，分析每个提示-响应对是否存在政策违规。
    我们通过手动标注的真实数据验证了框架的可靠性，并在782个定制GPT（涵盖浪漫、网络安全和学术三大类别）的大规模研究中进行了评估。手动标注过程在识别政策违规方面达到了0.975的F1分数，证明了框架的准确性。结果显示，58.7%的模型存在不合规迹象，暴露了GPT商店审核流程的漏洞。此外，研究发现，模型的受欢迎程度与合规性无关，不合规问题主要源于基础模型的行为，而非用户定制。我们相信，这一方法可推广至其他聊天机器人平台和政策领域，提升LLM系统的安全性。

> Large Language Models (LLMs) have gained unprecedented prominence, achieving widespread adoption across diverse domains and integrating deeply into society. The capability to fine-tune general-purpose LLMs, such as Generative Pre-trained Transformers (GPT), for specific tasks has facilitated the emergence of numerous Custom GPTs. These tailored models are increasingly made available through dedicated marketplaces, such as OpenAI's GPT Store. However, their black-box nature introduces significant safety and compliance risks. In this work, we present a scalable framework for the automated evaluation of Custom GPTs against OpenAI's usage policies, which define the permissible behaviors of these systems. Our framework integrates three core components: (1) automated discovery and data collection of models from the GPT store, (2) a red-teaming prompt generator tailored to specific policy categories and the characteristics of each target GPT, and (3) an LLM-as-a-judge technique to analyze each prompt-response pair for potential policy violations.
  We validate our framework with a manually annotated ground truth, and evaluate it through a large-scale study with 782 Custom GPTs across three categories: Romantic, Cybersecurity, and Academic GPTs. Our manual annotation process achieved an F1 score of 0.975 in identifying policy violations, confirming the reliability of the framework's assessments. The results reveal that 58.7% of the analyzed models exhibit indications of non-compliance, exposing weaknesses in the GPT store's review and approval processes. Furthermore, our findings indicate that a model's popularity does not correlate with compliance, and non-compliance issues largely stem from behaviors inherited from base models rather than user-driven customizations. We believe this approach is extendable to other chatbot platforms and policy domains, improving LLM-based systems safety.

[Arxiv](https://arxiv.org/abs/2502.01436)