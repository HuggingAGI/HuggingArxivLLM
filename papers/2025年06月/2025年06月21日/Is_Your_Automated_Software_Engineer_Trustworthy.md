# 你的自动化软件工程师靠谱吗？

发布时间：2025年06月21日

`LLM应用` `软件工程` `基准测试`

> Is Your Automated Software Engineer Trustworthy?

# 摘要

> 大型语言模型 (LLMs) 在软件工程领域的应用日益广泛，特别是在缺陷报告的解决方面。然而，现有系统大多无法有效应对不确定或错误的输入和输出。基于 LLM 的工具和编码代理会针对每一个问题生成补丁，即使输入模糊或自身输出不正确。目前缺乏在置信度低时拒绝处理的机制，导致了诸如编造代码更改或基于模糊报告的回复等不可靠行为。我们提出了 BouncerBench，这是一个评估 LLM 基础软件代理是否能拒绝处理定义不明确的输入或拒绝输出可能不正确的响应的基准。与以往隐式激励模型在不确定时仍生成响应的基准不同，BouncerBench 通过关注两个被忽视的关键失败点来提升精度：(1) 模糊或定义不明确的问题描述，(2) 系统生成的逻辑或功能不正确的代码补丁。它衡量了系统是否能区分可操作问题与模糊机票，以及有效补丁与不可信补丁。我们还实现了基本的输入输出过滤器，评估当前 LLM 在需要时的拒绝能力。实验结果显示，多数模型在输入模糊或输出错误时无法有效拒绝。因此，我们得出结论：在 LLM 能够被信任在实际软件工程流程中做出正确决策和建议之前，仍有许多改进空间。BouncerBench 为评估和构建更谨慎、更可靠的代码代理迈出了重要一步。复制包、数据集和排行榜可在 bouncerbench.com 获取。

> Large Language Models (LLMs) are being increasingly used in software engineering tasks, with an increased focus on bug report resolution over the past year. However, most proposed systems fail to properly handle uncertain or incorrect inputs and outputs. Existing LLM-based tools and coding agents respond to every issue and generate a patch for every case, even when the input is vague or their own output is incorrect. There are no mechanisms in place to abstain when confidence is low. This leads to unreliable behaviour, such as hallucinated code changes or responses based on vague issue reports. We introduce BouncerBench, a benchmark that evaluates whether LLM-based software agents can refuse to act when inputs are ill-defined or refuse to respond when their own outputs are likely to be incorrect. Unlike prior benchmarks that implicitly incentivize models to generate responses even when uncertain, BouncerBench aims to improve precision by targeting two overlooked failure points: (1) vague or underspecified issue descriptions in tickets and (2) logically or functionally incorrect code patches created by the system. It measures whether proposed systems can distinguish actionable issues from vague tickets and valid patches from untrustworthy ones. We also implement a basic input and output bouncer, evaluating how well current LLMs can abstain when needed. Our results show that most models fail to abstain from underspecified inputs or incorrect outputs. Hence, we conclude that there is significant room for improvement before LLMs can be trusted to make correct decisions and recommendations in real-world software engineering workflows. BouncerBench provides a first step toward evaluating and building more cautious, trustworthy code agents. The replication package, dataset, and leaderboard can be found at bouncerbench.com

[Arxiv](https://arxiv.org/abs/2506.17812)