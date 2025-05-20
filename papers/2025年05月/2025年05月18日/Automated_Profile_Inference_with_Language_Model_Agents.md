# 语言模型代理驱动的自动化档案推断

发布时间：2025年05月18日

`Agent`

> Automated Profile Inference with Language Model Agents

# 摘要

> 大型语言模型（LLMs）驱动的智能体在自动问题解决方面取得了令人瞩目的进展。然而，这些自动化能力也为恶意应用开辟了道路。本文研究了LLMs对在线匿名性构成的一种新型威胁——自动化档案推断。在这种威胁下，攻击者可指示LLMs自动抓取并从匿名平台上用户公开活动信息中提取敏感个人属性。我们还引入了一个名为AutoProfiler的自动化档案框架，用于评估此类威胁在现实场景中的可行性。AutoProfiler由四个专门的LLM代理组成，它们协同工作以收集和处理用户在线活动，并生成包含提取个人信息的档案。在两个现实数据集和一个合成数据集上的实验结果表明，AutoProfiler具有高度的有效性和效率，并且可以轻松大规模部署在网页端。我们证明，推断出的属性既敏感又可识别，存在重大的隐私泄露风险，例如去匿名化和敏感信息泄露。此外，我们从不同角度探讨了缓解策略，并呼吁公众提高对这一新兴在线匿名隐私威胁的认识。

> Impressive progress has been made in automated problem-solving by the collaboration of large language models (LLMs) based agents. However, these automated capabilities also open avenues for malicious applications. In this paper, we study a new threat that LLMs pose to online pseudonymity, called automated profile inference, where an adversary can instruct LLMs to automatically scrape and extract sensitive personal attributes from publicly visible user activities on pseudonymous platforms. We also introduce an automated profiling framework called AutoProfiler to assess the feasibility of such threats in real-world scenarios. AutoProfiler consists of four specialized LLM agents, who work collaboratively to collect and process user online activities and generate a profile with extracted personal information. Experimental results on two real-world datasets and one synthetic dataset demonstrate that AutoProfiler is highly effective and efficient, and can be easily deployed on a web scale. We demonstrate that the inferred attributes are both sensitive and identifiable, posing significant risks of privacy breaches, such as de-anonymization and sensitive information leakage. Additionally, we explore mitigation strategies from different perspectives and advocate for increased public awareness of this emerging privacy threat to online pseudonymity.

[Arxiv](https://arxiv.org/abs/2505.12402)