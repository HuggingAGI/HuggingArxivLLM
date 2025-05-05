# 辅助大型语言模型代理实现社交感知谈判对话

发布时间：2025年02月17日

`Agent`

> Assistive Large Language Model Agents for Socially-Aware Negotiation Dialogues

# 摘要

> 我们开发了基于大型语言模型（LLMs）的辅助代理，帮助谈判者在商业谈判中取得更好的结果。具体来说，我们通过让两个基于LLM的代理进行角色扮演来模拟商业谈判。第三个LLM则作为调解剂，负责重写违反规范的发言，以改善谈判结果。我们提出了一种无需调优、无需标签的In-Context Learning (ICL) 方法，用于为调解剂选择高质量的ICL示例，并在此过程中引入了一个新的评估标准，称为价值影响，用于衡量谈判结果的质量。我们通过丰富的实证证据展示了该方法在三个不同谈判主题中的有效性。我们的源代码和生成的数据集已发布在：https://github.com/tk1363704/SADAS。

> We develop assistive agents based on Large Language Models (LLMs) that aid interlocutors in business negotiations. Specifically, we simulate business negotiations by letting two LLM-based agents engage in role play. A third LLM acts as a remediator agent to rewrite utterances violating norms for improving negotiation outcomes. We introduce a simple tuning-free and label-free In-Context Learning (ICL) method to identify high-quality ICL exemplars for the remediator, where we propose a novel select criteria, called value impact, to measure the quality of the negotiation outcomes. We provide rich empirical evidence to demonstrate its effectiveness in negotiations across three different negotiation topics. We have released our source code and the generated dataset at: https://github.com/tk1363704/SADAS.

[Arxiv](https://arxiv.org/abs/2402.01737)