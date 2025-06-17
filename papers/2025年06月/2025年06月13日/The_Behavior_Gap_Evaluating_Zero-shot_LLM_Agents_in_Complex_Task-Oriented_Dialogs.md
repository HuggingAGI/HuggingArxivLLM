# 行为差距——零样本LLM代理在复杂任务型对话中的表现评测

发布时间：2025年06月13日

`Agent` `对话系统` `人工智能`

> The Behavior Gap: Evaluating Zero-shot LLM Agents in Complex Task-Oriented Dialogs

# 摘要

> 基于大语言模型（LLM）的智能体在任务导向对话系统（TODS）中发挥了重要作用，但在零样本场景下仍面临显著性能挑战。尽管先前研究注意到这一性能差距，但其背后的行为驱动因素尚未得到充分探索。本研究提出了一种全面的评估框架，用于量化AI智能体与人类专家之间的行为差距，重点关注对话行为、工具使用和知识利用方面的差异。研究发现，行为差距是影响LLM智能体性能的关键负面因素。值得注意的是，随着任务复杂性的增加，行为差距也随之扩大（相关性：0.963），导致智能体在处理复杂任务导向对话时性能下降。在我们研究中最复杂的任务中，即使是基于GPT-4o的智能体也表现出与人类行为的低度对齐，具体表现为对话行为的F1分数较低（0.464），工具使用过多且往往与目标不符（F1分数为0.139），以及对外部知识的无效利用。减少这种行为差距可带来显著的性能提升（平均24.3%）。本研究强调了全面行为评估和改进对齐策略的重要性，以增强基于LLM的TODS在处理复杂任务时的有效性。

> Large Language Model (LLM)-based agents have significantly impacted Task-Oriented Dialog Systems (TODS) but continue to face notable performance challenges, especially in zero-shot scenarios. While prior work has noted this performance gap, the behavioral factors driving the performance gap remain under-explored. This study proposes a comprehensive evaluation framework to quantify the behavior gap between AI agents and human experts, focusing on discrepancies in dialog acts, tool usage, and knowledge utilization. Our findings reveal that this behavior gap is a critical factor negatively impacting the performance of LLM agents. Notably, as task complexity increases, the behavior gap widens (correlation: 0.963), leading to a degradation of agent performance on complex task-oriented dialogs. For the most complex task in our study, even the GPT-4o-based agent exhibits low alignment with human behavior, with low F1 scores for dialog acts (0.464), excessive and often misaligned tool usage with a F1 score of 0.139, and ineffective usage of external knowledge. Reducing such behavior gaps leads to significant performance improvement (24.3% on average). This study highlights the importance of comprehensive behavioral evaluations and improved alignment strategies to enhance the effectiveness of LLM-based TODS in handling complex tasks.

[Arxiv](https://arxiv.org/abs/2506.12266)