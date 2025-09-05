# AR²：大型语言模型抽象推理的对抗性强化学习

发布时间：2025年08月27日

`强化学习` `基础理论`

> AR$^2$: Adversarial Reinforcement Learning for Abstract Reasoning in Large Language Models

# 摘要

> 抽象能力——即从复杂问题描述中识别并提炼关键计算模式的能力——是计算机科学的核心技能，对人类问题解决者和编码导向的大型语言模型（LLMs）都不可或缺。尽管近年来利用强化学习（RL）训练LLMs进行代码生成的技术不断进步，但现有方法大多停留在表面模式识别，忽视了对抽象能力的专门训练。为此，本研究提出AR²（面向抽象推理的对抗性强化学习）框架，旨在针对性增强LLMs的抽象能力。该框架通过教师模型将核心问题转化为富含叙事性的复杂描述（同时保留其基本逻辑），并训练学生编码模型通过提取这些问题的潜在计算核心来解决此类复杂叙事问题。实验结果显示，AR²显著提升了学生模型在未见过的高难度编程任务上的准确率，印证了抽象能力是提升LLM泛化性能的关键技能。

> Abstraction--the ability to recognize and distill essential computational patterns from complex problem statements--is a foundational skill in computer science, critical both for human problem-solvers and coding-oriented large language models (LLMs). Despite recent advances in training LLMs for code generation using reinforcement learning (RL), most existing approaches focus primarily on superficial pattern recognition, overlooking explicit training for abstraction. In this study, we propose AR$^2$ (Adversarial Reinforcement Learning for Abstract Reasoning), a novel framework explicitly designed to enhance the abstraction abilities of LLMs. AR$^2$ employs a teacher model to transform kernel problems into narrative-rich, challenging descriptions without changing their fundamental logic. Simultaneously, a student coding model is trained to solve these complex narrative problems by extracting their underlying computational kernels. Experimental results demonstrate that AR$^2$ substantially improves the student model's accuracy on previously unseen, challenging programming tasks, underscoring abstraction as a key skill for enhancing LLM generalization.

[Arxiv](https://arxiv.org/abs/2509.03537)