# 一种基于事件树的可进化交互代理任务驱动方法，用于提升应急决策支持

发布时间：2024年12月23日

`Agent

理由：这篇论文提出了一种基于事件树的可进化交互代理任务驱动法（EvoTaskTree），该方法结合了两种由大型语言模型（LLMs）驱动的代理：任务执行者和任务验证者。这些代理负责关键程序执行和行动有效性验证，并通过事件树分析进行学习和决策。因此，这篇论文主要关注的是代理（Agent）的设计和应用，属于Agent分类。` `应急管理`

> A Novel Task-Driven Method with Evolvable Interactive Agents Using Event Trees for Enhanced Emergency Decision Support

# 摘要

> 随着气候变化等全球性挑战加剧，不可预见的紧急情况频发，人类驱动策略在关键时刻的局限性愈发凸显。预先制定的应急计划不足，往往使操作员在复杂系统故障时手足无措。为此，我们提出了一种新颖的方法——EvoTaskTree（基于事件树的可进化交互代理任务驱动法），以应对各种突发事件的敏捷决策需求。该方法结合了两种由大型语言模型（LLMs）驱动的代理：任务执行者负责关键程序执行，任务验证者确保行动有效性。通过事件树分析，我们的框架涵盖了三大核心任务：事件子事件分析、事件树头事件分析及决策建议。代理从这些任务的成功与失败中学习。最后，我们以核电站为例，展示了这一方法在安全关键系统中的卓越表现。研究结果表明，EvoTaskTree不仅高效，且在处理全新事件场景时准确率高达100%，显著提升了紧急决策的制定速度。

> As climate change and other global challenges increase the likelihood of unforeseen emergencies, the limitations of human-driven strategies in critical situations become more pronounced. Inadequate pre-established emergency plans can lead operators to become overwhelmed during complex systems malfunctions. This study addresses the urgent need for agile decision-making in response to various unforeseen incidents through a novel approach, EvoTaskTree (a task-driven method with evolvable interactive agents using event trees for emergency decision support). This advanced approach integrates two types of agents powered by large language models (LLMs): task executors, responsible for executing critical procedures, and task validators, ensuring the efficacy of those actions. By leveraging insights from event tree analysis, our framework encompasses three crucial tasks: initiating event subevent analysis, event tree header event analysis, and decision recommendations. The agents learn from both successful and unsuccessful responses from these tasks. Finally, we use nuclear power plants as a demonstration of a safety-critical system. Our findings indicate that the designed agents are not only effective but also outperform existing approaches, achieving an impressive accuracy rate of up to 100 % in processing previously unencoun32 tered incident scenarios. This paper demonstrates that EvoTaskTree significantly enhances the rapid formulation of emergency decision-making.

[Arxiv](https://arxiv.org/abs/2501.06193)