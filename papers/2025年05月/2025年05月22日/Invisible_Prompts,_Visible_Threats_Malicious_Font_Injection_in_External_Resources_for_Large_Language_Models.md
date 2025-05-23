# 不可见的提示，可见的威胁：大型语言模型中外部资源的恶意字体注入

发布时间：2025年05月22日

`LLM应用` `网络安全` `人工智能`

> Invisible Prompts, Visible Threats: Malicious Font Injection in External Resources for Large Language Models

# 摘要

> 大型语言模型（LLMs）正逐渐配备实时网络搜索功能，并与模型上下文协议（MCP）等协议集成。这一扩展可能引入新的安全漏洞。我们系统地研究了通过在网页等外部资源中注入恶意字体，LLMs 对隐藏的对抗性提示的脆弱性。攻击者通过操纵代码到字形映射，注入对用户不可见的欺骗性内容。我们评估了两个关键攻击场景：(1) "恶意内容中继" 和 (2) "敏感数据泄露"，通过启用MCP的工具进行。实验表明，注入恶意字体的间接提示可通过外部资源绕过LLMs的安全机制，成功率因数据敏感性和提示设计而异。我们的研究强调了在处理外部内容时，增强LLMs部署安全措施的紧迫性。

> Large Language Models (LLMs) are increasingly equipped with capabilities of real-time web search and integrated with protocols like Model Context Protocol (MCP). This extension could introduce new security vulnerabilities. We present a systematic investigation of LLM vulnerabilities to hidden adversarial prompts through malicious font injection in external resources like webpages, where attackers manipulate code-to-glyph mapping to inject deceptive content which are invisible to users. We evaluate two critical attack scenarios: (1) "malicious content relay" and (2) "sensitive data leakage" through MCP-enabled tools. Our experiments reveal that indirect prompts with injected malicious font can bypass LLM safety mechanisms through external resources, achieving varying success rates based on data sensitivity and prompt design. Our research underscores the urgent need for enhanced security measures in LLM deployments when processing external content.

[Arxiv](https://arxiv.org/abs/2505.16957)