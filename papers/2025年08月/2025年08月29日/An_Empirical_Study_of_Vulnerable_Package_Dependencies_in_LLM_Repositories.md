# LLM仓库中脆弱包依赖的实证研究

发布时间：2025年08月29日

`LLM应用` `基础理论`

> An Empirical Study of Vulnerable Package Dependencies in LLM Repositories

# 摘要

> 大型语言模型（LLMs）近年来发展迅猛，为众多领域带来了颠覆性变革。尽管LLMs已广泛应用并取得成功，但其运行严重依赖包管理系统提供的外部代码依赖项，由此形成了错综复杂的LLM依赖供应链。这些依赖项一旦存在漏洞，便可能使LLMs面临安全风险。现有研究多聚焦于模型层面的安全威胁，而LLM依赖供应链中的漏洞问题却长期被忽视。为填补这一研究空白，我们对52个开源LLMs展开实证分析，深入核查其第三方依赖项及相关漏洞。随后，我们进一步调研了LLM代码库的维护活动，以探究开发者在实际操作中如何管理第三方漏洞。最后，我们将LLM生态系统与Python生态系统中的第三方依赖漏洞进行了对比分析。研究结果显示，LLM生态系统中半数漏洞的未披露时长超过56.2个月，这一周期远长于Python生态系统中的漏洞。此外，75.8%的LLMs在其配置文件中仍包含存在安全隐患的依赖项。本研究不仅深化了对LLM供应链风险的认知，还为相关从业者提供了实践启示，并指明了提升LLM供应链安全性的潜在方向。

> Large language models (LLMs) have developed rapidly in recent years, revolutionizing various fields. Despite their widespread success, LLMs heavily rely on external code dependencies from package management systems, creating a complex and interconnected LLM dependency supply chain. Vulnerabilities in dependencies can expose LLMs to security risks. While existing research predominantly focuses on model-level security threats, vulnerabilities within the LLM dependency supply chain have been overlooked. To fill this gap, we conducted an empirical analysis of 52 open-source LLMs, examining their third-party dependencies and associated vulnerabilities. We then explored activities within the LLM repositories to understand how maintainers manage third-party vulnerabilities in practice. Finally, we compared third-party dependency vulnerabilities in the LLM ecosystem to those in the Python ecosystem. Our results show that half of the vulnerabilities in the LLM ecosystem remain undisclosed for more than 56.2 months, significantly longer than those in the Python ecosystem. Additionally, 75.8% of LLMs include vulnerable dependencies in their configuration files. This study advances the understanding of LLM supply chain risks, provides insights for practitioners, and highlights potential directions for improving the security of the LLM supply chain.

[Arxiv](https://arxiv.org/abs/2508.21417)