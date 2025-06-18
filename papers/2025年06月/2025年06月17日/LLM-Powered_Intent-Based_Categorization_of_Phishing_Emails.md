# # 利用LLM进行意图驱动的钓鱼邮件分类
基于LLM的意图驱动钓鱼邮件分类

发布时间：2025年06月17日

`LLM应用` `网络安全` `威胁检测`

> LLM-Powered Intent-Based Categorization of Phishing Emails

# 摘要

> 网络钓鱼攻击不仅成功欺骗了人类，还绕过了旨在保护他们的防御机制，仍然是现代网络安全的重大威胁。传统检测系统主要关注用户在收件箱中不可见的电子邮件元数据，但面对钓鱼邮件时仍显力不从心，而有经验的用户往往仅凭文本内容就能识别出这些威胁。本文聚焦于大型语言模型 (LLMs) 的实际潜力，通过分析邮件意图来实现检测。除了传统的二元分类方法，我们还提出了一个意图类型分类法，借助LLMs将邮件划分为不同类别，从而生成可操作的威胁情报。为支持研究，我们整合公开数据集，创建了一个包含真实与钓鱼邮件的自定义数据集。实验结果表明，现有LLMs在钓鱼邮件检测与分类方面表现优异，充分展现了其在网络安全领域的应用前景。

> Phishing attacks remain a significant threat to modern cybersecurity, as they successfully deceive both humans and the defense mechanisms intended to protect them. Traditional detection systems primarily focus on email metadata that users cannot see in their inboxes. Additionally, these systems struggle with phishing emails, which experienced users can often identify empirically by the text alone. This paper investigates the practical potential of Large Language Models (LLMs) to detect these emails by focusing on their intent. In addition to the binary classification of phishing emails, the paper introduces an intent-type taxonomy, which is operationalized by the LLMs to classify emails into distinct categories and, therefore, generate actionable threat information. To facilitate our work, we have curated publicly available datasets into a custom dataset containing a mix of legitimate and phishing emails. Our results demonstrate that existing LLMs are capable of detecting and categorizing phishing emails, underscoring their potential in this domain.

[Arxiv](https://arxiv.org/abs/2506.14337)