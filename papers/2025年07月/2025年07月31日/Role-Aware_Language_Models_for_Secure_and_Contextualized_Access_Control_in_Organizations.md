# 面向组织的安全情境化访问控制的角色感知语言模型

发布时间：2025年07月31日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在企业环境中的应用，特别是如何通过微调使模型生成反映不同组织角色访问权限的响应。研究重点在于模型的应用和安全控制，属于LLM的应用层面。` `访问控制`

> Role-Aware Language Models for Secure and Contextualized Access Control in Organizations

# 摘要

> 随着大型语言模型（LLMs）在企业环境中的广泛应用，基于用户角色控制模型行为成为一项关键需求。现有的安全方法通常假设访问权限统一，主要关注防止有害或有毒的输出，但未涉及基于角色的访问限制。在本研究中，我们探讨了能否通过微调使LLMs生成反映不同组织角色访问权限的响应。我们采用了三种建模策略：基于BERT的分类器、基于LLM的分类器以及基于角色的条件生成。为了评估这些方法，我们构建了两个互补的数据集。第一个数据集通过聚类和角色标注，从现有的指令微调语料库中改编而来；第二个数据集则通过合成生成，以反映现实且基于角色的企业场景。我们评估了这些模型在不同组织结构下的表现，并分析了它们在面对提示注入、角色错配和越狱尝试时的鲁棒性。

> As large language models (LLMs) are increasingly deployed in enterprise settings, controlling model behavior based on user roles becomes an essential requirement. Existing safety methods typically assume uniform access and focus on preventing harmful or toxic outputs, without addressing role-specific access constraints. In this work, we investigate whether LLMs can be fine-tuned to generate responses that reflect the access privileges associated with different organizational roles. We explore three modeling strategies: a BERT-based classifier, an LLM-based classifier, and role-conditioned generation. To evaluate these approaches, we construct two complementary datasets. The first is adapted from existing instruction-tuning corpora through clustering and role labeling, while the second is synthetically generated to reflect realistic, role-sensitive enterprise scenarios. We assess model performance across varying organizational structures and analyze robustness to prompt injection, role mismatch, and jailbreak attempts.

[Arxiv](https://arxiv.org/abs/2507.23465)