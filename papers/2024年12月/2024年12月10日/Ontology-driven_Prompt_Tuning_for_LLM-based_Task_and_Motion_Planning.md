# 基于 LLM 的任务和运动规划的本体驱动提示调整

发布时间：2024年12月10日

`LLM应用` `任务规划` `动态环境`

> Ontology-driven Prompt Tuning for LLM-based Task and Motion Planning

# 摘要

> 在动态环境中执行复杂操作任务，需要高效的任务和运动规划（TAMP）方法，它将高层符号规划与低层运动规划相结合。像 GPT-4 这样的大型语言模型（LLMs）的进步，正通过提供自然语言这种直观灵活的方式来描述任务、生成符号规划和进行推理，改变着任务规划。但基于 LLM 的 TAMP 方法因静态和基于模板的提示而效果有限，难以适应动态环境和复杂任务情境。为解决这些局限，本研究提出一种新颖的本体驱动的提示调整框架，运用基于知识的推理，借助任务上下文推理和基于知识的环境状态描述来优化和拓展用户提示。将特定领域知识融入提示，能确保任务规划语义准确且具备上下文感知。所提框架通过解决符号规划生成中的语义错误（比如在涉及分层对象放置的场景中保持逻辑时间目标顺序）证明了其有效性。该框架通过模拟和真实场景得到验证，在适应动态环境和生成语义正确的任务规划方面，相比基线方法有显著提升。

> Performing complex manipulation tasks in dynamic environments requires efficient Task and Motion Planning (TAMP) approaches, which combine high-level symbolic plan with low-level motion planning. Advances in Large Language Models (LLMs), such as GPT-4, are transforming task planning by offering natural language as an intuitive and flexible way to describe tasks, generate symbolic plans, and reason. However, the effectiveness of LLM-based TAMP approaches is limited due to static and template-based prompting, which struggles in adapting to dynamic environments and complex task contexts. To address these limitations, this work proposes a novel ontology-driven prompt-tuning framework that employs knowledge-based reasoning to refine and expand user prompts with task contextual reasoning and knowledge-based environment state descriptions. Integrating domain-specific knowledge into the prompt ensures semantically accurate and context-aware task plans. The proposed framework demonstrates its effectiveness by resolving semantic errors in symbolic plan generation, such as maintaining logical temporal goal ordering in scenarios involving hierarchical object placement. The proposed framework is validated through both simulation and real-world scenarios, demonstrating significant improvements over the baseline approach in terms of adaptability to dynamic environments, and the generation of semantically correct task plans.

[Arxiv](https://arxiv.org/abs/2412.07493)