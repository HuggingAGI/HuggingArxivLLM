# # 自动化配置文件推断与语言模型代理
基于语言模型代理的自动化配置文件推断是一种创新方法，旨在利用语言模型的强大语义理解和推理能力，实现更高效、更智能的配置管理。这种方法通过减少人工干预，提高系统的自动化水平，同时提升配置文件的准确性和一致性。

发布时间：2025年05月18日

`LLM应用

摘要讨论了大语言模型（LLMs）在自动化档案推断中的应用，属于将LLMs应用于特定场景的研究，因此归类为LLM应用。` `隐私保护` `网络匿名`

> Automated Profile Inference with Language Model Agents

# 摘要

> 大语言模型（LLMs）代理在自动化问题解决方面取得了令人瞩目的进展。然而，这些自动化能力也为恶意应用开辟了道路。本文研究了 LLMs 对在线匿名性构成的一种新型威胁——自动化档案推断（automated profile inference）。在这种威胁下，攻击者可指示 LLMs 自动抓取并从匿名平台上的公开用户活动中提取敏感个人属性。我们还引入了一个名为 AutoProfiler 的自动化档案构建框架，用于评估此类威胁在现实场景中的可行性。AutoProfiler 由四个专业的 LLM 代理组成，它们协同工作，收集和处理用户的在线活动，并生成包含提取的个人信息的档案。实验结果表明，AutoProfiler 在两个真实数据集和一个合成数据集上表现出色，不仅高效，而且可以轻松扩展到大规模网络应用。我们证明，推断出的属性不仅敏感且可识别，这带来了严重的隐私泄露风险，如去匿名化和敏感信息泄露。此外，我们从不同角度探讨了缓解策略，并呼吁公众提高对这一新兴匿名性威胁的认识。

> Impressive progress has been made in automated problem-solving by the collaboration of large language models (LLMs) based agents. However, these automated capabilities also open avenues for malicious applications. In this paper, we study a new threat that LLMs pose to online pseudonymity, called automated profile inference, where an adversary can instruct LLMs to automatically scrape and extract sensitive personal attributes from publicly visible user activities on pseudonymous platforms. We also introduce an automated profiling framework called AutoProfiler to assess the feasibility of such threats in real-world scenarios. AutoProfiler consists of four specialized LLM agents, who work collaboratively to collect and process user online activities and generate a profile with extracted personal information. Experimental results on two real-world datasets and one synthetic dataset demonstrate that AutoProfiler is highly effective and efficient, and can be easily deployed on a web scale. We demonstrate that the inferred attributes are both sensitive and identifiable, posing significant risks of privacy breaches, such as de-anonymization and sensitive information leakage. Additionally, we explore mitigation strategies from different perspectives and advocate for increased public awareness of this emerging privacy threat to online pseudonymity.

[Arxiv](https://arxiv.org/abs/2505.12402)