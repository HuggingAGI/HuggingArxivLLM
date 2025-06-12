# # 摘要
好奇的语言模型：战略性测试时信息获取

发布时间：2025年06月10日

`Agent` `决策科学` `人工智能`

> The Curious Language Model: Strategic Test-Time Information Acquisition

# 摘要

> 面对信息不足的决策困境，决策者通常会采取行动获取所需信息，如咨询专家或进行实验。然而，不同信息获取方式的成本差异，使得如何选择既具信息价值又经济实惠的行动成为关键挑战。针对这一问题，我们提出了CuriosiTree——一种基于启发式的、用于大型语言模型（LLMs）零样本信息获取的推理时策略。CuriosiTree通过贪婪树搜索评估每项行动的预期信息增益，并在预期收益与成本之间寻求平衡，从而做出战略性选择。在临床诊断模拟中，CuriosiTree展现了其整合异质信息源的成本效益，并在选择有助于准确诊断的动作序列方面超越了传统策略。

> Decision-makers often possess insufficient information to render a confident decision. In these cases, the decision-maker can often undertake actions to acquire the necessary information about the problem at hand, e.g., by consulting knowledgeable authorities or by conducting experiments. Importantly, different levers of information acquisition come with different costs, posing the challenge of selecting the actions that are both informative and cost-effective. In this work, we propose CuriosiTree, a heuristic-based, test-time policy for zero-shot information acquisition in large language models (LLMs). CuriosiTree employs a greedy tree search to estimate the expected information gain of each action and strategically chooses actions based on a balance of anticipated information gain and associated cost. Empirical validation in a clinical diagnosis simulation shows that CuriosiTree enables cost-effective integration of heterogenous sources of information, and outperforms baseline action selection strategies in selecting action sequences that enable accurate diagnosis.

[Arxiv](https://arxiv.org/abs/2506.09173)