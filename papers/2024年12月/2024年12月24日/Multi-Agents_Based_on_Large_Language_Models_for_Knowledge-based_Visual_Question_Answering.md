# 基于大型语言模型的多智能体应用于基于知识的视觉问答

发布时间：2024年12月24日

`Agent` `视觉问答` `人工智能`

> Multi-Agents Based on Large Language Models for Knowledge-based Visual Question Answering

# 摘要

> 大型语言模型（LLMs）在基于知识的视觉问答（VQA）领域成果斐然。但现有方法仍面临挑战：无法自主运用外部工具，也难以团队协作。人类在碰到新问题时，通常清楚是否需用外部工具，比如面对熟悉的问题，往往能直接作答，而遇到陌生问题时，则倾向使用搜索引擎之类的工具。另外，人类还倾向与他人合作探讨以获取更优答案。受此启发，我们提出了多智能体投票框架。我们设计了三个基于LLM的智能体，模拟团队中不同层级的人员，并按层级分配可用工具。每个智能体给出相应答案，最后对所有智能体提供的答案进行投票，得出最终答案。在OK-VQA和A-OKVQA上的实验显示，我们的方法分别比其他基线高出2.2和1.0。

> Large Language Models (LLMs) have achieved impressive results in knowledge-based Visual Question Answering (VQA). However existing methods still have challenges: the inability to use external tools autonomously, and the inability to work in teams. Humans tend to know whether they need to use external tools when they encounter a new question, e.g., they tend to be able to give a direct answer to a familiar question, whereas they tend to use tools such as search engines when they encounter an unfamiliar question. In addition, humans also tend to collaborate and discuss with others to get better answers. Inspired by this, we propose the multi-agent voting framework. We design three LLM-based agents that simulate different levels of staff in a team, and assign the available tools according to the levels. Each agent provides the corresponding answer, and finally all the answers provided by the agents are voted to get the final answer. Experiments on OK-VQA and A-OKVQA show that our approach outperforms other baselines by 2.2 and 1.0, respectively.

[Arxiv](https://arxiv.org/abs/2412.18351)