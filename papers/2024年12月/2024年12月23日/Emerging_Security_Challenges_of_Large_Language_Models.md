# 大型语言模型面临的新兴安全挑战

发布时间：2024年12月23日

`LLM应用` `网络安全` `人工智能`

> Emerging Security Challenges of Large Language Models

# 摘要

> 大型语言模型（LLMs）在短时间内于众多不同领域，包括教育[4]、医疗保健[23]等高重要性领域，实现了创纪录的应用。LLMs 是基于多样数据训练的开放式模型，并非专为特定下游任务定制，因而能在各领域广泛适用。它们常被用于文本生成，也广泛协助代码生成[3]，甚至如微软安全副驾驶[18]所示用于安全信息分析。传统机器学习（ML）模型易受对抗性攻击[9]。正因对大规模采用 LLMs 潜在安全影响的担忧，成立了此关于 LLMs 安全性的工作组。在“网络攻击检测与防御 - 人工智能驱动的威胁与响应”的达格斯图尔研讨会上，工作组的讨论聚焦于 LLMs 对对抗性攻击的脆弱性，而非其在生成恶意软件或促成网络攻击方面的潜在用途。虽注意到后者代表的潜在威胁，但 LLMs 在这类用途中主要充当发展的加速器，类似其在良性使用中的作用。为使分析更具体，工作组以 ChatGPT 作为 LLMs 的具体实例，并探讨了以下几点，这也构成了本报告的框架：1. LLMs 在脆弱性方面与传统 ML 模型有何差异？2. LLMs 的攻击目标是什么？3. 评估 LLMs 脆弱性所带来风险的复杂程度如何？4. LLMs 的供应链是怎样的，数据如何在系统中进出，又有哪些安全影响？最后，我们对开放挑战和前景进行了综述。

> Large language models (LLMs) have achieved record adoption in a short period of time across many different sectors including high importance areas such as education [4] and healthcare [23]. LLMs are open-ended models trained on diverse data without being tailored for specific downstream tasks, enabling broad applicability across various domains. They are commonly used for text generation, but also widely used to assist with code generation [3], and even analysis of security information, as Microsoft Security Copilot demonstrates [18]. Traditional Machine Learning (ML) models are vulnerable to adversarial attacks [9]. So the concerns on the potential security implications of such wide scale adoption of LLMs have led to the creation of this working group on the security of LLMs. During the Dagstuhl seminar on "Network Attack Detection and Defense - AI-Powered Threats and Responses", the working group discussions focused on the vulnerability of LLMs to adversarial attacks, rather than their potential use in generating malware or enabling cyberattacks. Although we note the potential threat represented by the latter, the role of the LLMs in such uses is mostly as an accelerator for development, similar to what it is in benign use. To make the analysis more specific, the working group employed ChatGPT as a concrete example of an LLM and addressed the following points, which also form the structure of this report: 1. How do LLMs differ in vulnerabilities from traditional ML models? 2. What are the attack objectives in LLMs? 3. How complex it is to assess the risks posed by the vulnerabilities of LLMs? 4. What is the supply chain in LLMs, how data flow in and out of systems and what are the security implications? We conclude with an overview of open challenges and outlook.

[Arxiv](https://arxiv.org/abs/2412.17614)