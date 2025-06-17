# LLM 在安全咨询调查中的应用：我们还有多远？

发布时间：2025年06月16日

`LLM应用` `软件安全` `网络安全`

> Using LLMs for Security Advisory Investigations: How Far Are We?

# 摘要

> 大型语言模型（LLMs）在软件安全领域的应用日益广泛，但其生成准确漏洞公告的可信度仍有待验证。本研究旨在探讨ChatGPT在以下三个方面的性能：(1) 根据CVE编号生成合理的安全公告，(2) 区分真实与虚假的CVE编号，(3) 从公告描述中提取CVE编号。通过使用一个包含100个真实CVE编号和100个虚假CVE编号的整理数据集，我们手动分析了模型输出的可信度和一致性。结果显示，ChatGPT为96%的真实输入CVE编号和97%的虚假输入CVE编号生成了合理的安全公告，这表明其在区分真实与虚假编号方面存在一定局限性。此外，当将这些生成的公告重新输入ChatGPT以识别其原始CVE编号时，模型在6%的情况下从真实公告中生成了虚假CVE编号。这些发现凸显了ChatGPT在网络安全应用中的优势与局限。虽然该模型在自动化公告生成方面展现出潜力，但其无法可靠验证CVE编号或在重新评估时保持一致性的能力，凸显了其在关键安全任务部署中的潜在风险。本研究强调在网络安全工作流程中谨慎使用LLMs的重要性，并建议进一步改进其设计以提高安全公告生成的可靠性和适用性。

> Large Language Models (LLMs) are increasingly used in software security, but their trustworthiness in generating accurate vulnerability advisories remains uncertain. This study investigates the ability of ChatGPT to (1) generate plausible security advisories from CVE-IDs, (2) differentiate real from fake CVE-IDs, and (3) extract CVE-IDs from advisory descriptions. Using a curated dataset of 100 real and 100 fake CVE-IDs, we manually analyzed the credibility and consistency of the model's outputs. The results show that ChatGPT generated plausible security advisories for 96% of given input real CVE-IDs and 97% of given input fake CVE-IDs, demonstrating a limitation in differentiating between real and fake IDs. Furthermore, when these generated advisories were reintroduced to ChatGPT to identify their original CVE-ID, the model produced a fake CVE-ID in 6% of cases from real advisories. These findings highlight both the strengths and limitations of ChatGPT in cybersecurity applications. While the model demonstrates potential for automating advisory generation, its inability to reliably authenticate CVE-IDs or maintain consistency upon re-evaluation underscores the risks associated with its deployment in critical security tasks. Our study emphasizes the importance of using LLMs with caution in cybersecurity workflows and suggests the need for further improvements in their design to improve reliability and applicability in security advisory generation.

[Arxiv](https://arxiv.org/abs/2506.13161)