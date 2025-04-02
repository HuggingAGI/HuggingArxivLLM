# 视觉环境交互规划助力具身复杂问答任务

发布时间：2025年04月01日

`Agent` `机器人` `人工智能`

> Visual Environment-Interactive Planning for Embodied Complex-Question Answering

# 摘要

> 本研究专注于具身复杂问答任务，旨在让机器人理解结构复杂、语义抽象的人类问题。核心在于根据视觉环境感知进行合理规划。现有方法多采用一次性规划，依赖大型模型但对环境理解不足。本文提出了一种多步规划框架，按顺序制定计划。为确保处理复杂问题的能力，我们构建了一个结构化的语义空间，通过分层视觉感知和问题本质的链式表达实现迭代交互，从而支持顺序任务规划。在框架中，我们首先基于视觉分层场景图解析人类语言，明确问题意图。然后引入外部规则制定当前步骤计划，减少对大型模型的依赖。每个计划生成都基于视觉反馈，通过多轮交互直至获得答案。这种方法支持持续反馈与调整，使机器人优化行动策略。为验证框架，我们创建了一个包含更复杂问题的新数据集。实验结果表明，我们的方法在复杂任务上表现出色且稳定，并在现实场景中展现出良好的可行性，具有实际应用价值。


> This study focuses on Embodied Complex-Question Answering task, which means the embodied robot need to understand human questions with intricate structures and abstract semantics. The core of this task lies in making appropriate plans based on the perception of the visual environment. Existing methods often generate plans in a once-for-all manner, i.e., one-step planning. Such approach rely on large models, without sufficient understanding of the environment. Considering multi-step planning, the framework for formulating plans in a sequential manner is proposed in this paper. To ensure the ability of our framework to tackle complex questions, we create a structured semantic space, where hierarchical visual perception and chain expression of the question essence can achieve iterative interaction. This space makes sequential task planning possible. Within the framework, we first parse human natural language based on a visual hierarchical scene graph, which can clarify the intention of the question. Then, we incorporate external rules to make a plan for current step, weakening the reliance on large models. Every plan is generated based on feedback from visual perception, with multiple rounds of interaction until an answer is obtained. This approach enables continuous feedback and adjustment, allowing the robot to optimize its action strategy. To test our framework, we contribute a new dataset with more complex questions. Experimental results demonstrate that our approach performs excellently and stably on complex tasks. And also, the feasibility of our approach in real-world scenarios has been established, indicating its practical applicability.

[Arxiv](https://arxiv.org/abs/2504.00775)