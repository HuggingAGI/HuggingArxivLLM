# 自我解释性：LLMs不仅能够清晰描述驱动决策的复杂内部流程，还能够在训练过程中持续优化。

发布时间：2025年05月21日

`LLM理论` `可解释性` `透明性`

> Self-Interpretability: LLMs Can Describe Complex Internal Processes that Drive Their Decisions, and Improve with Training

# 摘要

> 我们对大型语言模型 (LLMs) 的工作原理和行为机制仍知之甚少。尽管神经网络的解释性难题尚未完全解决，但我们已经开始尝试解析其中的神经元和电路功能。另一种理解这些系统的方法是探究并开发它们进行自我反思和解释自身运作机制的能力。我们的研究表明：i) 当代 LLMs 能够在特定决策过程中提供准确的内部过程描述；ii) 通过训练可以提升这些能力；iii) 这种训练在一定程度上具有泛化能力。为此，我们对 GPT-4o 和 GPT-4o-mini 进行了微调，使其能够在选择公寓、贷款、假期等复杂情境中，根据随机生成的定量偏好（例如公寓中自然光线与安静环境的相对重要性）做出决策。我们发现，LLMs 能够准确报告这些偏好（即他们在决策过程中学到的不同属性的权重）。进一步研究显示，这些 LLMs 可以通过微调来更准确地解释其决策过程。更重要的是，这种训练具有泛化能力：它不仅提升了模型在经过微调训练后所掌握的复杂决策中准确解释自身行为的能力，还提升了其在其他复杂决策中的类似能力。这项工作朝着训练 LLMs 准确且广泛地报告自身内部过程的目标迈进了一步，这将极大提升模型的可解释性、控制性和安全性。

> We have only limited understanding of how and why large language models (LLMs) respond in the ways that they do. Their neural networks have proven challenging to interpret, and we are only beginning to tease out the function of individual neurons and circuits within them. However, another path to understanding these systems is to investigate and develop their capacity to introspect and explain their own functioning. Here, we show that i) contemporary LLMs are capable of providing accurate, quantitative descriptions of their own internal processes during certain kinds of decision-making, ii) that it is possible to improve these capabilities through training, and iii) that this training generalizes to at least some degree. To do so, we fine-tuned GPT-4o and GPT-4o-mini to make decisions in a wide variety of complex contexts (e.g., choosing between condos, loans, vacations, etc.) according to randomly-generated, quantitative preferences about how to weigh different attributes during decision-making (e.g., the relative importance of natural light versus quiet surroundings for condos). We demonstrate that the LLMs can accurately report these preferences (i.e., the weights that they learned to give to different attributes during decision-making). Next, we demonstrate that these LLMs can be fine-tuned to explain their decision-making even more accurately. Finally, we demonstrate that this training generalizes: It improves the ability of the models to accurately explain what they are doing as they make other complex decisions, not just decisions they have learned to make via fine-tuning. This work is a step towards training LLMs to accurately and broadly report on their own internal processes -- a possibility that would yield substantial benefits for interpretability, control, and safety.

[Arxiv](https://arxiv.org/abs/2505.17120)