# 在我们中间：一个用于智能体欺骗的沙盒环境

发布时间：2025年04月05日

`Agent` `人工智能`

> Among Us: A Sandbox for Agentic Deception

# 摘要

> 研究AI代理中的欺骗行为既重要又充满挑战，因为缺乏能够自然引发这种行为的模型和沙盒环境，而无需让模型在特定条件下行动或故意植入后门。我们基于文本的社交推理游戏环境$	extit{AmongAgents}$进行扩展，通过引入Among Us作为一个丰富的沙盒环境来解决这一问题，其中LLM代理在与其他代理或人类互动时会自然而然地展现出类似人类的欺骗行为。我们引入了Deception ELO作为一种无界衡量欺骗能力的指标，表明前沿模型获胜更多是因为它们更擅长欺骗，而非更擅长识别欺骗。我们在Among Us中评估了AI安全技术（如监控LLM输出、在各种数据集上使用线性探针以及稀疏自动编码器）在检测谎言和欺骗方面的有效性，并发现这些技术在分布外数据上表现非常出色。我们开源了我们的沙盒环境作为未来对齐研究的基准，希望这能成为一个良好的测试平台，用于改进检测和消除由代理动机驱动的欺骗行为的安全技术，并预测LLM中的欺骗能力。

> Studying deception in AI agents is important and difficult due to the lack of model organisms and sandboxes that elicit the behavior without asking the model to act under specific conditions or inserting intentional backdoors. Extending upon $\textit{AmongAgents}$, a text-based social-deduction game environment, we aim to fix this by introducing Among Us as a rich sandbox where LLM-agents exhibit human-style deception naturally while they think, speak, and act with other agents or humans. We introduce Deception ELO as an unbounded measure of deceptive capability, suggesting that frontier models win more because they're better at deception, not at detecting it. We evaluate the effectiveness of AI safety techniques (LLM-monitoring of outputs, linear probes on various datasets, and sparse autoencoders) for detecting lying and deception in Among Us, and find that they generalize very well out-of-distribution. We open-source our sandbox as a benchmark for future alignment research and hope that this is a good testbed to improve safety techniques to detect and remove agentically-motivated deception, and to anticipate deceptive abilities in LLMs.

[Arxiv](https://arxiv.org/abs/2504.04072)