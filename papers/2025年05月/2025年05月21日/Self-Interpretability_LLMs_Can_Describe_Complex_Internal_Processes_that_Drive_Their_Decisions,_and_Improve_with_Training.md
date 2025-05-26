# # 自我解释性：LLMs能描述影响决策的复杂内部机制，并在训练中不断优化

发布时间：2025年05月21日

`LLM理论` `决策支持`

> Self-Interpretability: LLMs Can Describe Complex Internal Processes that Drive Their Decisions, and Improve with Training

# 摘要

> 大型语言模型（LLMs）的内部工作机制仍有许多未解之谜。尽管它们的神经网络难以捉摸，但我们发现了一条新的研究路径：让模型学会自我反思和解释自己的运作方式。研究发现，当代LLMs在特定决策过程中能够提供准确的内部机制描述，而且这种能力可以通过训练进一步提升，并且具有一定的通用性。

我们对GPT-4o和GPT-4o-mini进行了微调训练，让它们在选择公寓、贷款、假期等复杂场景中，根据随机生成的不同属性权重偏好做出决策。实验表明，这些模型不仅能够准确报告这些偏好（即它们在决策过程中赋予不同属性的权重），还能够通过进一步训练更清晰地解释自己的决策过程。更重要的是，这种训练效果具有通用性，不仅提升了模型在特定任务中的解释能力，也增强了它们在其他复杂决策场景中的自我解释能力。

这项研究为训练LLMs更准确、更全面地报告自身内部机制迈出了重要一步，这将极大提升模型的可解释性、可控性和安全性。

> We have only limited understanding of how and why large language models (LLMs) respond in the ways that they do. Their neural networks have proven challenging to interpret, and we are only beginning to tease out the function of individual neurons and circuits within them. However, another path to understanding these systems is to investigate and develop their capacity to introspect and explain their own functioning. Here, we show that i) contemporary LLMs are capable of providing accurate, quantitative descriptions of their own internal processes during certain kinds of decision-making, ii) that it is possible to improve these capabilities through training, and iii) that this training generalizes to at least some degree. To do so, we fine-tuned GPT-4o and GPT-4o-mini to make decisions in a wide variety of complex contexts (e.g., choosing between condos, loans, vacations, etc.) according to randomly-generated, quantitative preferences about how to weigh different attributes during decision-making (e.g., the relative importance of natural light versus quiet surroundings for condos). We demonstrate that the LLMs can accurately report these preferences (i.e., the weights that they learned to give to different attributes during decision-making). Next, we demonstrate that these LLMs can be fine-tuned to explain their decision-making even more accurately. Finally, we demonstrate that this training generalizes: It improves the ability of the models to accurately explain what they are doing as they make other complex decisions, not just decisions they have learned to make via fine-tuning. This work is a step towards training LLMs to accurately and broadly report on their own internal processes -- a possibility that would yield substantial benefits for interpretability, control, and safety.

[Arxiv](https://arxiv.org/abs/2505.17120)