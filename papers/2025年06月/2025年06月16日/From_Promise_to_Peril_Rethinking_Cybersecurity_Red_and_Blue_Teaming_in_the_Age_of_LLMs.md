# 从希望到危险：LLM时代下网络安全红蓝队的再思考

发布时间：2025年06月16日

`LLM应用` `网络安全` `人工智能`

> From Promise to Peril: Rethinking Cybersecurity Red and Blue Teaming in the Age of LLMs

# 摘要

> 大型语言模型 (LLMs) 正在改变网络安全领域，通过赋能红队和蓝队的操作展现其独特价值。红队可借助 LLMs 制定攻击策略、创作钓鱼内容、模拟对手行为以及生成漏洞利用代码。而蓝队则能利用它们进行威胁情报整合、根因分析及文档自动化。这种双重能力既带来了变革的机遇，也伴随着不容忽视的风险。
    本文档深入探讨了 LLMs 在 MITRE ATT&CK 和 NIST 网络安全框架 (CSF) 中的应用场景，系统性地剖析了其当前优势与局限。尽管 LLMs 在多种任务中表现出了强大的适应性，但在高风险、语境复杂的环境中仍显脆弱。其主要局限包括生成错误信息、语境记忆不足、推理能力有限以及对输入提示的敏感性，这些都影响了其在实际应用中的可靠性。
    此外，LLMs 的实际应用还引发了关于双重用途风险、对抗性滥用以及人类监督减少的担忧。恶意行为者可能利用 LLMs 自动化攻击准备、隐藏攻击路径，并降低复杂攻击的技术门槛。
    为确保更安全的落地，我们建议采用人工在环监督、增强模型可解释性、引入隐私保护机制以及构建抵御对抗性攻击的强健系统。随着组织逐步拥抱 AI 驱动的网络安全，深入理解 LLMs 的风险与实际影响对于最大化其防御价值并减少潜在副作用至关重要。

> Large Language Models (LLMs) are set to reshape cybersecurity by augmenting red and blue team operations. Red teams can exploit LLMs to plan attacks, craft phishing content, simulate adversaries, and generate exploit code. Conversely, blue teams may deploy them for threat intelligence synthesis, root cause analysis, and streamlined documentation. This dual capability introduces both transformative potential and serious risks.
  This position paper maps LLM applications across cybersecurity frameworks such as MITRE ATT&CK and the NIST Cybersecurity Framework (CSF), offering a structured view of their current utility and limitations. While LLMs demonstrate fluency and versatility across various tasks, they remain fragile in high-stakes, context-heavy environments. Key limitations include hallucinations, limited context retention, poor reasoning, and sensitivity to prompts, which undermine their reliability in operational settings.
  Moreover, real-world integration raises concerns around dual-use risks, adversarial misuse, and diminished human oversight. Malicious actors could exploit LLMs to automate reconnaissance, obscure attack vectors, and lower the technical threshold for executing sophisticated attacks.
  To ensure safer adoption, we recommend maintaining human-in-the-loop oversight, enhancing model explainability, integrating privacy-preserving mechanisms, and building systems robust to adversarial exploitation. As organizations increasingly adopt AI driven cybersecurity, a nuanced understanding of LLMs' risks and operational impacts is critical to securing their defensive value while mitigating unintended consequences.

[Arxiv](https://arxiv.org/abs/2506.13434)