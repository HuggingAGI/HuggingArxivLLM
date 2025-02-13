# # 商用LLM代理已易受简单却危险的攻击

发布时间：2025年02月12日

`Agent` `人工智能`

> Commercial LLM Agents Are Already Vulnerable to Simple Yet Dangerous Attacks

# 摘要

> 近期机器学习安全研究大量聚焦于针对对齐的大型语言模型（LLMs）的攻击手段。这些攻击可能窃取私密信息，或迫使模型生成有害内容。在实际应用中，LLMs通常集成于包含记忆系统、检索功能、网络访问及API调用的智能体管道中。这些附加组件引入了新的安全漏洞，使得这些由LLMs驱动的智能体相较于孤立的LLMs更易受攻击，但针对LLM智能体安全性的研究却相对匮乏。本文致力于分析仅适用于LLM智能体的独特安全与隐私漏洞。我们首先按威胁来源、攻击目标、切入点、攻击可见性、攻击策略及智能体管道固有弱点，构建了一套攻击分类体系。随后，我们对 popular open-source 和商业智能体实施了一系列示例攻击，直观展示了其安全漏洞的实际影响。值得注意的是，我们的攻击手段实现简单，完全无需机器学习专业知识。

> A high volume of recent ML security literature focuses on attacks against aligned large language models (LLMs). These attacks may extract private information or coerce the model into producing harmful outputs. In real-world deployments, LLMs are often part of a larger agentic pipeline including memory systems, retrieval, web access, and API calling. Such additional components introduce vulnerabilities that make these LLM-powered agents much easier to attack than isolated LLMs, yet relatively little work focuses on the security of LLM agents. In this paper, we analyze security and privacy vulnerabilities that are unique to LLM agents. We first provide a taxonomy of attacks categorized by threat actors, objectives, entry points, attacker observability, attack strategies, and inherent vulnerabilities of agent pipelines. We then conduct a series of illustrative attacks on popular open-source and commercial agents, demonstrating the immediate practical implications of their vulnerabilities. Notably, our attacks are trivial to implement and require no understanding of machine learning.

[Arxiv](https://arxiv.org/abs/2502.08586)