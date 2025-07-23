# StaAgent：测试静态分析器的智能体框架

发布时间：2025年07月20日

`LLM应用` `软件工程`

> StaAgent: An Agentic Framework for Testing Static Analyzers

# 摘要

> 静态分析工具在软件开发生命周期早期发现漏洞方面至关重要，但它们的规则实现往往测试不足且容易不一致。为了解决这一问题，我们提出了StaAgent——一个基于LLM的智能框架，能够系统性地评估静态分析器的规则。StaAgent由四个专门代理组成：种子生成代理将漏洞检测规则转化为具体漏洞诱导程序；代码验证代理确保种子的正确性；变异生成代理生成语义等价的变异程序；分析器评估代理通过比较种子及其变异程序的行为执行变异测试。通过揭示不一致行为，StaAgent帮助发现规则实现中的缺陷。这个LLM驱动的多代理框架为提升静态分析器可靠性提供了可扩展且灵活的解决方案。我们在五种先进LLM（CodeLlama、DeepSeek、Codestral、Qwen和GPT-4）和五种主流静态分析器（SpotBugs、SonarQube、ErrorProne、Infer和PMD）上评估了StaAgent。实验结果显示，我们的方法成功揭示了这五种静态分析器最新版本中的64个问题规则（SpotBugs 28个，SonarQube 18个，ErrorProne 6个，Infer 4个，PMD 8个）。其中53个漏洞无法被最先进基线检测到。我们已将所有漏洞报告给开发人员，目前两个已修复，三个已确认，其余正在等待回复。这些结果不仅验证了我们方法的有效性，也凸显了基于智能体的LLM驱动数据合成在软件工程中的巨大潜力。

> Static analyzers play a critical role in identifying bugs early in the software development lifecycle, but their rule implementations are often under-tested and prone to inconsistencies. To address this, we propose StaAgent, an agentic framework that harnesses the generative capabilities of Large Language Models (LLMs) to systematically evaluate static analyzer rules. StaAgent comprises four specialized agents: a Seed Generation Agent that translates bug detection rules into concrete, bug-inducing seed programs; a Code Validation Agent that ensures the correctness of these seeds; a Mutation Generation Agent that produces semantically equivalent mutants; and an Analyzer Evaluation Agent that performs metamorphic testing by comparing the static analyzer's behavior on seeds and their corresponding mutants. By revealing inconsistent behaviors, StaAgent helps uncover flaws in rule implementations. This LLM-driven, multi-agent framework offers a scalable and adaptable solution to improve the reliability of static analyzers. We evaluated StaAgent with five state-of-the-art LLMs (CodeL-lama, DeepSeek, Codestral, Qwen, and GPT-4o) across five widely used static analyzers (SpotBugs, SonarQube, ErrorProne, Infer, and PMD). The experimental results show that our approach can help reveal 64 problematic rules in the latest versions of these five static analyzers (i.e., 28 in SpotBugs, 18 in SonarQube, 6 in ErrorProne, 4 in Infer, and 8 in PMD). In addition, 53 out of the 64 bugs cannot be detected by the SOTA baseline. We have reported all the bugs to developers, with two of them already fixed. Three more have been confirmed by developers, while the rest are awaiting response. These results demonstrate the effectiveness of our approach and underscore the promise of agentic, LLM-driven data synthesis to advance software engineering.

[Arxiv](https://arxiv.org/abs/2507.15892)