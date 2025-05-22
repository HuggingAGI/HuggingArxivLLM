# 大型语言模型推理的自我进化课程

发布时间：2025年05月20日

`LLM应用`

> Self-Evolving Curriculum for LLM Reasoning

# 摘要

> 强化学习（RL）在提升大型语言模型（LLMs）的推理能力方面表现出色，尤其在数学和代码生成等领域效果显著。然而，RL微调的成功高度依赖于训练课程的设计，即如何安排训练问题的呈现顺序。当前的课程设计方法存在诸多局限：随机课程虽简单易行，但效果有限；手动设计的课程往往过于依赖启发式规则；而在线过滤方法又可能因计算成本过高而不切实际。针对这些问题，我们提出了一种名为自我演化课程（SEC）的自动化课程学习方法，能够在RL微调过程中动态优化课程策略。我们的方法将课程选择建模为一个非平稳的多臂老虎机问题，其中每个问题类别（如难度级别或问题类型）被视为独立的臂。我们采用策略梯度方法中的绝对优势作为即时学习收益的代理度量，指导课程策略的选择。在每个训练步骤中，课程策略会根据TD(0)方法更新，以最大化奖励信号。通过在规划、归纳推理和数学三个推理领域的实验，我们发现SEC显著提升了模型的推理能力，使其能够更有效地泛化到更复杂、分布外的测试问题。此外，当同时对多个推理领域进行微调时，SEC还能够实现更好的技能平衡。这些结果表明，自我演化课程（SEC）是一种极具潜力的强化学习微调策略，为大型语言模型的优化提供了新的思路。


> Reinforcement learning (RL) has proven effective for fine-tuning large language models (LLMs), significantly enhancing their reasoning abilities in domains such as mathematics and code generation. A crucial factor influencing RL fine-tuning success is the training curriculum: the order in which training problems are presented. While random curricula serve as common baselines, they remain suboptimal; manually designed curricula often rely heavily on heuristics, and online filtering methods can be computationally prohibitive. To address these limitations, we propose Self-Evolving Curriculum (SEC), an automatic curriculum learning method that learns a curriculum policy concurrently with the RL fine-tuning process. Our approach formulates curriculum selection as a non-stationary Multi-Armed Bandit problem, treating each problem category (e.g., difficulty level or problem type) as an individual arm. We leverage the absolute advantage from policy gradient methods as a proxy measure for immediate learning gain. At each training step, the curriculum policy selects categories to maximize this reward signal and is updated using the TD(0) method. Across three distinct reasoning domains: planning, inductive reasoning, and mathematics, our experiments demonstrate that SEC significantly improves models' reasoning capabilities, enabling better generalization to harder, out-of-distribution test problems. Additionally, our approach achieves better skill balance when fine-tuning simultaneously on multiple reasoning domains. These findings highlight SEC as a promising strategy for RL fine-tuning of LLMs.

[Arxiv](https://arxiv.org/abs/2505.14970)