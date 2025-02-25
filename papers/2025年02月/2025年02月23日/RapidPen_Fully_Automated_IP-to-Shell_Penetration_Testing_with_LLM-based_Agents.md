# RapidPen：基于 LLM 的智能代理实现 IP 到 Shell 的全自动渗透测试

发布时间：2025年02月23日

`LLM应用` `渗透测试`

> RapidPen: Fully Automated IP-to-Shell Penetration Testing with LLM-based Agents

# 摘要

> 我们很高兴推出RapidPen——一个全新的完全自动化渗透测试框架，致力于解决无需人工干预的初始立足点（IP-to-Shell）挑战。与以往专注于攻击后利用或需要人工参与的方法不同，RapidPen创新性地利用大型语言模型（LLMs）从单一IP地址出发，自主完成漏洞发现与利用。

RapidPen的核心在于将先进的ReAct式任务规划（Re）与增强的成功攻击案例知识库相结合，辅以命令生成和直接执行反馈循环（Act），从而实现服务的系统性扫描、攻击向量的智能识别以及自动化精准攻击。

在针对Hack The Box平台易受攻击目标的评估中，RapidPen展现出卓越的性能：以每运行约$0.3-$0.6的成本，在200-400秒内成功获得Shell权限。当复用先前的“成功案例”数据时，其成功率更是达到了60%。这一结果充分证明了完全自主渗透测试的巨大潜力。

RapidPen的应用前景广阔：没有专门安全团队的组织可以借此快速识别关键漏洞；而经验丰富的渗透测试人员则能将精力从重复性工作中解放出来，专注于更具挑战性的任务。我们希望通过RapidPen，让渗透测试变得更加普及和经济高效，从而为现代软件生态的安全性保驾护航。

> We present RapidPen, a fully automated penetration testing (pentesting) framework that addresses
  the challenge of achieving an initial foothold (IP-to-Shell) without human intervention. Unlike prior
  approaches that focus primarily on post-exploitation or require a human-in-the-loop, RapidPen
  leverages large language models (LLMs) to autonomously discover and exploit vulnerabilities, starting from
  a single IP address. By integrating advanced ReAct-style task planning (Re) with retrieval-augmented
  knowledge bases of successful exploits, along with a command-generation and direct execution feedback loop
  (Act), RapidPen systematically scans services, identifies viable attack vectors, and executes targeted
  exploits in a fully automated manner.
  In our evaluation against a vulnerable target from the Hack The Box platform, RapidPen achieved shell
  access within 200-400 seconds at a per-run cost of approximately \$0.3-\$0.6, demonstrating a
  60\% success rate when reusing prior "success-case" data. These results underscore the potential
  of truly autonomous pentesting for both security novices and seasoned professionals. Organizations
  without dedicated security teams can leverage RapidPen to quickly identify critical vulnerabilities,
  while expert pentesters can offload repetitive tasks and focus on complex challenges.
  Ultimately, our work aims to make penetration testing more accessible and cost-efficient,
  thereby enhancing the overall security posture of modern software ecosystems.

[Arxiv](https://arxiv.org/abs/2502.16730)