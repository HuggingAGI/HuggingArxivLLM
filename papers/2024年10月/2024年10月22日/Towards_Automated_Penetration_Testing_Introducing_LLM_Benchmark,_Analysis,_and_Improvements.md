# 迈向自动化渗透测试：LLM基准、分析与改进的引入

发布时间：2024年10月22日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）进行自动化渗透测试，并提出了一个基于LLM的开放基准。论文的核心是LLM在网络安全领域的应用，特别是如何利用LLM来改进渗透测试工具（如PentestGPT）。因此，这篇论文应归类为LLM应用。` `网络安全` `渗透测试`

> Towards Automated Penetration Testing: Introducing LLM Benchmark, Analysis, and Improvements

# 摘要

> # 摘要
黑客攻击对网络安全构成重大威胁，每年造成数十亿美元损失。为应对这一风险，道德黑客攻击（即渗透测试）被用于识别系统和网络中的漏洞。近年来，大型语言模型（LLMs）在包括网络安全在内的多个领域展现出巨大潜力。然而，目前尚缺乏一个全面的、开放的、端到端的自动化渗透测试基准，以推动进展并评估这些模型在安全环境中的能力。本文提出了一种基于LLM的自动化渗透测试新型开放基准，填补了这一关键空白。我们首先使用最先进的PentestGPT工具评估了LLMs（包括GPT-4o和Llama 3.1-405B）的性能。结果显示，尽管Llama 3.1在某些方面优于GPT-4o，但两者目前均无法完全自动化地进行端到端渗透测试。随后，我们推进了现有技术，并通过消融研究为改进PentestGPT工具提供了见解。研究揭示了LLMs在渗透测试各个环节（如枚举、利用和权限提升）中面临的挑战。这项工作为AI辅助网络安全领域贡献了新知识，并为未来基于大型语言模型的自动化渗透测试研究奠定了基础。

> Hacking poses a significant threat to cybersecurity, inflicting billions of dollars in damages annually. To mitigate these risks, ethical hacking, or penetration testing, is employed to identify vulnerabilities in systems and networks. Recent advancements in large language models (LLMs) have shown potential across various domains, including cybersecurity. However, there is currently no comprehensive, open, end-to-end automated penetration testing benchmark to drive progress and evaluate the capabilities of these models in security contexts. This paper introduces a novel open benchmark for LLM-based automated penetration testing, addressing this critical gap. We first evaluate the performance of LLMs, including GPT-4o and Llama 3.1-405B, using the state-of-the-art PentestGPT tool. Our findings reveal that while Llama 3.1 demonstrates an edge over GPT-4o, both models currently fall short of performing fully automated, end-to-end penetration testing. Next, we advance the state-of-the-art and present ablation studies that provide insights into improving the PentestGPT tool. Our research illuminates the challenges LLMs face in each aspect of Pentesting, e.g. enumeration, exploitation, and privilege escalation. This work contributes to the growing body of knowledge on AI-assisted cybersecurity and lays the foundation for future research in automated penetration testing using large language models.

[Arxiv](https://arxiv.org/abs/2410.17141)