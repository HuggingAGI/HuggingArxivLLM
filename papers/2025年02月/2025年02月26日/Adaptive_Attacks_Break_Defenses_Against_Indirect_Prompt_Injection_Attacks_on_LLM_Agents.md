# 自适应攻击突破防御：针对LLM代理的间接提示注入攻击。

发布时间：2025年02月26日

`LLM应用

理由：论文主要讨论了大型语言模型（LLM）代理在与环境交互中的应用及其面临的安全风险，特别是间接提示注入攻击。研究评估了防御方案的有效性，并提出了自适应攻击方法，属于LLM在实际应用中的安全问题，因此归类为LLM应用。` `人工智能`

> Adaptive Attacks Break Defenses Against Indirect Prompt Injection Attacks on LLM Agents

# 摘要

> 大型语言模型（LLM）代理借助外部工具与环境交互，在多样化应用中表现优异。然而，这一优势也带来了安全风险，尤其是间接提示注入（IPI）攻击的威胁。尽管已有针对IPI攻击的防御措施，但这些方案的可靠性仍需质疑，原因在于缺乏对自适应攻击的充分验证。本研究评估了八种防御方案，并通过自适应攻击手段成功突破所有防线，攻击成功率始终保持在50%以上。这一结果凸显了现有防御机制的脆弱性。我们的研究表明，在设计防御方案时，必须纳入自适应攻击评估环节，以确保其稳健与可靠。代码已开源，详情请访问https://github.com/uiuc-kang-lab/AdaptiveAttackAgent。

> Large Language Model (LLM) agents exhibit remarkable performance across diverse applications by using external tools to interact with environments. However, integrating external tools introduces security risks, such as indirect prompt injection (IPI) attacks. Despite defenses designed for IPI attacks, their robustness remains questionable due to insufficient testing against adaptive attacks. In this paper, we evaluate eight different defenses and bypass all of them using adaptive attacks, consistently achieving an attack success rate of over 50%. This reveals critical vulnerabilities in current defenses. Our research underscores the need for adaptive attack evaluation when designing defenses to ensure robustness and reliability. The code is available at https://github.com/uiuc-kang-lab/AdaptiveAttackAgent.

[Arxiv](https://arxiv.org/abs/2503.00061)