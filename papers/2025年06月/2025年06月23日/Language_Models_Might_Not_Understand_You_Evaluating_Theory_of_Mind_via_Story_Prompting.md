# # 摘要  
近期的进展使大型语言模型（LLMs）能够生成连贯且情境恰当的回应，然而，这些模型是否具备心理理论能力仍不明朗。本文研究了LLMs是否能通过故事提示推理他人的信念、欲望和意图，这种方法要求模型处理叙事场景，并基于人物的心理状态预测结果。实验结果显示，尽管LLMs能够生成合理的回应，但它们常常无法持续推理他人的心理状态，这凸显了现有模型在理解类人社会认知方面的局限性。

发布时间：2025年06月23日

`LLM应用` `模型评估`

> Language Models Might Not Understand You: Evaluating Theory of Mind via Story Prompting

# 摘要

> 我们推出$	exttt{StorySim}$——一个可编程的框架，用于合成生成故事，旨在评估大型语言模型（LLMs）的心理理论（ToM）和世界建模（WM）能力。与现有基准不同，$	exttt{StorySim}$生成的故事具有高度可控性，基于可调节的$	exttt{Storyboard}$，能够精准控制角色视角和事件，避免了预训练数据污染的问题。我们利用该框架设计了第一和第二阶心理理论任务，以及用于测试跟踪和建模心理状态能力的世界建模任务。实验结果表明，在一系列最先进的LLMs中，大多数模型在世界建模任务上的表现优于心理理论任务，并且模型在处理人类角色时的推理能力优于无生命物体。此外，我们的框架揭示了模型存在启发式行为的证据，例如近因效应和过度依赖故事中的早期事件。所有用于生成数据和评估的代码均可免费获取。

> We introduce $\texttt{StorySim}$, a programmable framework for synthetically generating stories to evaluate the theory of mind (ToM) and world modeling (WM) capabilities of large language models (LLMs). Unlike prior benchmarks that may suffer from contamination in pretraining data, $\texttt{StorySim}$ produces novel, compositional story prompts anchored by a highly controllable $\texttt{Storyboard}$, enabling precise manipulation of character perspectives and events. We use this framework to design first- and second-order ToM tasks alongside WM tasks that control for the ability to track and model mental states. Our experiments across a suite of state-of-the-art LLMs reveal that most models perform better on WM tasks than ToM tasks, and that models tend to perform better reasoning with humans compared to inanimate objects. Additionally, our framework enabled us to find evidence of heuristic behavior such as recency bias and an over-reliance on earlier events in the story. All code for generating data and evaluations is freely available.

[Arxiv](https://arxiv.org/abs/2506.19089)