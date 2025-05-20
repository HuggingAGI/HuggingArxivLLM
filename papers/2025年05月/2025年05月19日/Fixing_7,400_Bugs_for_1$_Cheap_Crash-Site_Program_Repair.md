# 修复7,400个错误，只需1美元：低成本崩溃现场程序修复

发布时间：2025年05月19日

`LLM应用` `软件工程` `漏洞修复`

> Fixing 7,400 Bugs for 1$: Cheap Crash-Site Program Repair

# 摘要

> 漏洞查找技术的快速发展发现了大量开发人员难以及时修复的漏洞，这迫切需要有效的自动化程序修复（APR）方法。然而，现代漏洞的复杂性常常使得精准的故障根源分析变得困难且不可靠。为应对这一挑战，我们提出了崩溃点修复方法，旨在简化修复任务的同时降低漏洞被利用的风险。此外，我们引入了一种基于模板的补丁生成方法，这种方法在保持高效和有效的同时，大幅降低了大型语言模型（LLMs）的token成本。

我们实现了我们的原型系统WILLIAMT，并将其与最先进的APR工具进行了对比评估。实验结果显示，当与性能最佳的代理CodeRover-S结合使用时，WILLIAMT在真实开源软件漏洞基准测试集ARVO上将token成本降低了45.9%，并将漏洞修复率提升至73.5%（+29.6%）。此外，我们还证明了即使无法访问前沿的LLMs，WILLIAMT依然能够有效运行：即使是在Mac M4 Mini上运行的本地模型，也达到了合理的修复率。这些结果凸显了WILLIAMT的广泛应用前景和可扩展性。


> The rapid advancement of bug-finding techniques has led to the discovery of more vulnerabilities than developers can reasonably fix, creating an urgent need for effective Automated Program Repair (APR) methods. However, the complexity of modern bugs often makes precise root cause analysis difficult and unreliable. To address this challenge, we propose crash-site repair to simplify the repair task while still mitigating the risk of exploitation. In addition, we introduce a template-guided patch generation approach that significantly reduces the token cost of Large Language Models (LLMs) while maintaining both efficiency and effectiveness.
  We implement our prototype system, WILLIAMT, and evaluate it against state-of-the-art APR tools. Our results show that, when combined with the top-performing agent CodeRover-S, WILLIAMT reduces token cost by 45.9% and increases the bug-fixing rate to 73.5% (+29.6%) on ARVO, a ground-truth open source software vulnerabilities benchmark. Furthermore, we demonstrate that WILLIAMT can function effectively even without access to frontier LLMs: even a local model running on a Mac M4 Mini achieves a reasonable repair rate. These findings highlight the broad applicability and scalability of WILLIAMT.

[Arxiv](https://arxiv.org/abs/2505.13103)