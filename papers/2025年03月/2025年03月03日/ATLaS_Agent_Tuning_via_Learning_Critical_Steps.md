# ATLaS：基于关键步骤学习的智能体调优方法

发布时间：2025年03月03日

`LLM应用` `智能代理` `通用人工智能`

> ATLaS: Agent Tuning via Learning Critical Steps

# 摘要

> 大型语言模型（LLM）代理在多领域任务中展现了卓越的泛化能力。然而，现有代理调整方法通常采用完整专家轨迹的监督微调，这可能引入专家偏见并限制对未覆盖状态的泛化能力。关键步骤如规划、复杂推理和战略决策对代理任务的成功至关重要，因此掌握这些步骤是提升LLM代理的核心。为了实现更高效和有效的调整，我们提出了ATLaS方法，该方法识别专家轨迹中的关键步骤，并仅基于这些步骤进行微调以降低成本。通过聚焦少数关键步骤，ATLaS减少了对完整轨迹过拟合的风险，同时提升了跨环境和任务的泛化能力。实验结果表明，仅基于ATLaS方法选择的30%关键步骤微调的LLM，其性能优于基于全部步骤微调的LLM和近期开源代理。ATLaS使LLM作为通用型代理，在与多样化环境交互的同时，维持并提升了基础技能。

> Large Language Model (LLM) agents have demonstrated remarkable generalization capabilities across multi-domain tasks. Existing agent tuning approaches typically employ supervised finetuning on entire expert trajectories. However, behavior-cloning of full trajectories can introduce expert bias and weaken generalization to states not covered by the expert data. Additionally, critical steps, such as planning, complex reasoning for intermediate subtasks, and strategic decision-making, are essential to success in agent tasks, so learning these steps is the key to improving LLM agents. For more effective and efficient agent tuning, we propose ATLaS that identifies the critical steps in expert trajectories and finetunes LLMs solely on these steps with reduced costs. By steering the training's focus to a few critical steps, our method mitigates the risk of overfitting entire trajectories and promotes generalization across different environments and tasks. In extensive experiments, an LLM finetuned on only 30% critical steps selected by ATLaS outperforms the LLM finetuned on all steps and recent open-source LLM agents. ATLaS maintains and improves base LLM skills as generalist agents interacting with diverse environments.

[Arxiv](https://arxiv.org/abs/2503.02197)