# 奖励模型通过以准确率为代价换取更高的吞吐量，使代码验证具备可扩展性。

发布时间：2025年06月11日

`LLM应用` `软件工程` `编程工具`

> Reward Models Enable Scalable Code Verification by Trading Accuracy for Throughput

# 摘要

> 通过大型语言模型（LLMs）解决编码任务的标准范式是生成-然后-排名程序，其中排名过程中的后一步骤使用了验证器。普遍共识认为，应当优先使用全面验证器（例如完整的测试套件），而非结果奖励模型（ORM），但这一观点忽视了其中的权衡。我们旨在通过系统性地探索速度与准确性的权衡来挑战这一假设。我们发现，ORM在通过以速度换取准确性的方式扩展验证方面发挥着关键作用，即使全面验证器可用时也是如此。在生成-剪枝-然后-排名的方法中，ORM的价值尤为突出：更快但不太准确的验证器在排名前剔除错误的解决方案——最终系统比完整测试套件快11.65倍，仅损失8.33%的准确性。我们分析了生成-剪枝-然后-排名的方法，并展示了其通过过滤掉错误但排名较高的解决方案来实现目标。这些发现为设计可扩展且准确的程序排名系统提供了指导。


> The standard paradigm for solving coding tasks via large language models (LLMs) is to generate-then-rank programs, where the latter step uses a verifier in the ranking process. The growing consensus is that a comprehensive verifier (e.g., a full test suite) should be prioritized over an outcome reward model (ORM) whenever possible, with little consideration given to the trade-offs involved. We aim to challenge this assumption by systematically exploring the tradeoff between speed and accuracy. We find that ORMs play a crucial role in scaling verification through trading accuracy for speed, even when a comprehensive verifier is available. Their value becomes especially apparent when used in a generate-prune-then-rank approach, where a faster but less accurate verifier removes incorrect solutions prior to ranking -- leading to a system that is 11.65x faster while only being 8.33% less accurate than the full test suite. We analyze the generate-prune-then-rank approach and show that it works by filtering out incorrect but highly ranked solutions. These findings enable the design of scalable and accurate program ranking systems.

[Arxiv](https://arxiv.org/abs/2506.10056)