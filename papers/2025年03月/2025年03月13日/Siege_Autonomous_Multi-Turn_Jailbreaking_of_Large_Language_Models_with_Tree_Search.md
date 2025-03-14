# 围攻：自主多轮越狱大型语言模型的树搜索方法

发布时间：2025年03月13日

`LLM应用` `模型安全` `模型测试`

> Siege: Autonomous Multi-Turn Jailbreaking of Large Language Models with Tree Search

# 摘要

> 我们提出了Siege，一个从树搜索视角模拟LLM安全性逐渐被侵蚀的多轮对抗框架。与依赖单一精心设计提示的单轮越狱攻击不同，Siege在每一轮对话中以广度优先的方式扩展对话，生成多个利用前文响应部分合规性的对抗性提示。通过追踪这些逐步泄露的策略漏洞并将其重新注入后续查询，Siege揭示了小的让步如何累积成完全被禁止的输出。在JailbreakBench数据集上的评估显示，Siege在GPT-3.5-turbo上实现了100%的成功率，在GPT-4上达到了97%，且所需查询次数少于Crescendo或GOAT等基准方法。这种树搜索方法为模型安全机制在连续对话轮次中的退化提供了深入见解，突显了对语言模型进行健壮多轮测试的紧迫性。

> We introduce Siege, a multi-turn adversarial framework that models the gradual erosion of Large Language Model (LLM) safety through a tree search perspective. Unlike single-turn jailbreaks that rely on one meticulously engineered prompt, Siege expands the conversation at each turn in a breadth-first fashion, branching out multiple adversarial prompts that exploit partial compliance from previous responses. By tracking these incremental policy leaks and re-injecting them into subsequent queries, Siege reveals how minor concessions can accumulate into fully disallowed outputs. Evaluations on the JailbreakBench dataset show that Siege achieves a 100% success rate on GPT-3.5-turbo and 97% on GPT-4 in a single multi-turn run, using fewer queries than baselines such as Crescendo or GOAT. This tree search methodology offers an in-depth view of how model safeguards degrade over successive dialogue turns, underscoring the urgency of robust multi-turn testing procedures for language models.

[Arxiv](https://arxiv.org/abs/2503.10619)