# ResearchTown：人类研究社区的模拟器

发布时间：2024年12月23日

`Agent` `科学研究` `多智能体框架`

> ResearchTown: Simulator of Human Research Community

# 摘要

> 大型语言模型（LLMs）在科学领域展现出非凡潜力，然而有个根本问题尚未有答案：能否用 LLMs 模拟人类研究群体？解决此问题能加深对创意头脑风暴过程的理解，还能激发新科学见解的自动发现。在这项工作中，我们提出了 ResearchTown，一个用于研究群体模拟的多智能体框架。在此框架内，人类研究群体被简化并建模为智能体 - 数据图，其中研究人员和论文分别被视作智能体类型和数据类型的节点，并依其合作关系相连接。我们还引入了 TextGNN，这是一个基于文本的推理框架，将各种研究活动（如论文阅读、论文写作和评论写作）建模为智能体 - 数据图上统一消息传递过程的特殊形式。为评估研究模拟的质量，我们推出了 ResearchBench，这是一个基于相似性，通过节点掩码预测任务进行可扩展和客观评估的基准。我们的实验得出三个关键发现：（1）ResearchTown 能为包括论文写作和评论写作在内的协作研究活动提供逼真模拟；（2）ResearchTown 在多个研究人员和多样论文的情况下能保持强大的模拟能力；（3）ResearchTown 能生成跨学科研究想法，有可能开拓新的研究方向。

> Large Language Models (LLMs) have demonstrated remarkable potential in scientific domains, yet a fundamental question remains unanswered: Can we simulate human research communities with LLMs? Addressing this question can deepen our understanding of the processes behind idea brainstorming and inspire the automatic discovery of novel scientific insights. In this work, we propose ResearchTown, a multi-agent framework for research community simulation. Within this framework, the human research community is simplified and modeled as an agent-data graph, where researchers and papers are represented as agent-type and data-type nodes, respectively, and connected based on their collaboration relationships. We also introduce TextGNN, a text-based inference framework that models various research activities (e.g., paper reading, paper writing, and review writing) as special forms of a unified message-passing process on the agent-data graph. To evaluate the quality of the research simulation, we present ResearchBench, a benchmark that uses a node-masking prediction task for scalable and objective assessment based on similarity. Our experiments reveal three key findings: (1) ResearchTown can provide a realistic simulation of collaborative research activities, including paper writing and review writing; (2) ResearchTown can maintain robust simulation with multiple researchers and diverse papers; (3) ResearchTown can generate interdisciplinary research ideas that potentially inspire novel research directions.

[Arxiv](https://arxiv.org/abs/2412.17767)