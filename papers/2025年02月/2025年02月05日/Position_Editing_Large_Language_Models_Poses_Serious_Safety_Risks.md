# 观点：编辑大型语言模型存在重大安全隐患

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）的知识编辑方法（KEs）及其潜在的安全风险。论文的核心内容涉及LLMs的理论层面，特别是如何修改模型中的知识以及这些修改可能带来的安全问题。因此，这篇论文更适合归类为LLM理论。` `人工智能安全` `模型编辑`

> Position: Editing Large Language Models Poses Serious Safety Risks

# 摘要

> 大型语言模型（LLMs）存储了大量世界知识，但这些知识可能随时间过时。为此，知识编辑方法（KEs）应运而生，它们能在副作用有限的情况下修改LLMs中的特定事实。然而，本文指出，编辑LLMs潜藏着严重的安全风险，而这些风险尚未得到足够重视。首先，KEs具有易获取、低成本、高性能和隐蔽性等特点，使其成为恶意行为者的理想工具。其次，我们展示了KEs如何被轻易用于多种恶意目的。第三，AI生态系统中存在漏洞，允许未经验证的模型上传和下载。第四，社会和机构意识的不足加剧了这一风险，并对各利益相关者产生了深远影响。我们呼吁社区：（i）研究防篡改模型和应对恶意编辑的措施；（ii）积极参与AI生态系统的安全防护。

> Large Language Models (LLMs) contain large amounts of facts about the world. These facts can become outdated over time, which has led to the development of knowledge editing methods (KEs) that can change specific facts in LLMs with limited side effects. This position paper argues that editing LLMs poses serious safety risks that have been largely overlooked. First, we note the fact that KEs are widely available, computationally inexpensive, highly performant, and stealthy makes them an attractive tool for malicious actors. Second, we discuss malicious use cases of KEs, showing how KEs can be easily adapted for a variety of malicious purposes. Third, we highlight vulnerabilities in the AI ecosystem that allow unrestricted uploading and downloading of updated models without verification. Fourth, we argue that a lack of social and institutional awareness exacerbates this risk, and discuss the implications for different stakeholders. We call on the community to (i) research tamper-resistant models and countermeasures against malicious model editing, and (ii) actively engage in securing the AI ecosystem.

[Arxiv](https://arxiv.org/abs/2502.02958)