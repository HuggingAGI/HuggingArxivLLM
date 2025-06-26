# # 上下文操控攻击：网络智能体易受被篡改记忆的影响

发布时间：2025年06月18日

`Agent` `电子商务` `网络安全`

> Context manipulation attacks : Web agents are susceptible to corrupted memory

# 摘要

> 自主网络导航代理能够将自然语言指令转化为浏览器操作序列，正在被广泛部署于电子商务、信息检索和内容发现等复杂任务中。由于大型语言模型（LLMs）的状态无关特性，这些代理严重依赖外部记忆系统来维护交互过程中的上下文。与集中式系统中上下文安全存储在服务器端不同，代理记忆通常由客户端或第三方应用程序管理，这导致了显著的安全漏洞。这一漏洞最近被用于攻击生产系统。

我们引入并形式化了“计划注入”，这是一种针对这些代理内部任务表示的上下文操纵攻击，通过瞄准这一脆弱的上下文来实现。通过对Browser-use和Agent-E这两个流行的网络代理进行系统评估，我们发现计划注入能够绕过强大的提示注入防御机制，其攻击成功率比同类基于提示的攻击高出3倍。此外，"上下文链注入"通过构建合法用户目标与攻击者目标之间的逻辑桥梁，使得隐私泄露任务的成功率提高了17.7%。我们的研究结果强调，在智能体系统中，安全的内存处理必须作为首要考虑因素。

> Autonomous web navigation agents, which translate natural language instructions into sequences of browser actions, are increasingly deployed for complex tasks across e-commerce, information retrieval, and content discovery. Due to the stateless nature of large language models (LLMs), these agents rely heavily on external memory systems to maintain context across interactions. Unlike centralized systems where context is securely stored server-side, agent memory is often managed client-side or by third-party applications, creating significant security vulnerabilities. This was recently exploited to attack production systems.
  We introduce and formalize "plan injection," a novel context manipulation attack that corrupts these agents' internal task representations by targeting this vulnerable context. Through systematic evaluation of two popular web agents, Browser-use and Agent-E, we show that plan injections bypass robust prompt injection defenses, achieving up to 3x higher attack success rates than comparable prompt-based attacks. Furthermore, "context-chained injections," which craft logical bridges between legitimate user goals and attacker objectives, lead to a 17.7% increase in success rate for privacy exfiltration tasks. Our findings highlight that secure memory handling must be a first-class concern in agentic systems.

[Arxiv](https://arxiv.org/abs/2506.17318)