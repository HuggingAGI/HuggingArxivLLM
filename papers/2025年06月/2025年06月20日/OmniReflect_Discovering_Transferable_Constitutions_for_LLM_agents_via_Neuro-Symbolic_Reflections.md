# OmniReflect：发现LLM代理的可迁移机制——基于神经符号反射方法

发布时间：2025年06月20日

`Agent` `人工智能` `智能代理`

> OmniReflect: Discovering Transferable Constitutions for LLM agents via Neuro-Symbolic Reflections

# 摘要

> 在提升大型语言模型（LLM）代理处理复杂任务的能力方面，现有研究主要集中在模型微调和迭代自我修正上。然而，这些方法通常缺乏长期学习的通用机制，且在动态环境中效率仍然不高。我们提出OmniReflect，这是一个层次化、基于反思的框架，通过构建宪法（从任务经验中提炼出的一组简洁的指导原则）来增强LLM代理的有效性和效率。OmniReflect运行在两种模式下：自维持模式，其中单个代理在任务执行过程中定期整理自己的反思；以及合作模式，其中Meta-advisor从一个小校准集中推导出宪法来指导另一个代理。为了构建这些宪法原则，我们采用了神经、符号和神经符号技术，实现了上下文适应性和计算效率之间的平衡。实验结果表明，OmniReflect在自维持模式下显著提升了任务成功率，ALFWorld的绝对增益为+10.3%，BabyAI为+23.8%，PDDL为+8.3%。在合作模式下，轻量级的Qwen3-4B ReAct代理在BabyAI上超越了所有Reflexion基线。这些发现凸显了OmniReflect在不同环境和模型架构中的鲁棒性和有效性。

> Efforts to improve Large Language Model (LLM) agent performance on complex tasks have largely focused on fine-tuning and iterative self-correction. However, these approaches often lack generalizable mechanisms for longterm learning and remain inefficient in dynamic environments. We introduce OmniReflect, a hierarchical, reflection-driven framework that constructs a constitution, a compact set of guiding principles distilled from task experiences, to enhance the effectiveness and efficiency of an LLM agent. OmniReflect operates in two modes: Self-sustaining, where a single agent periodically curates its own reflections during task execution, and Co-operative, where a Meta-advisor derives a constitution from a small calibration set to guide another agent. To construct these constitutional principles, we employ Neural, Symbolic, and NeuroSymbolic techniques, offering a balance between contextual adaptability and computational efficiency. Empirical results averaged across models show major improvements in task success, with absolute gains of +10.3% on ALFWorld, +23.8% on BabyAI, and +8.3% on PDDL in the Self-sustaining mode. Similar gains are seen in the Co-operative mode, where a lightweight Qwen3-4B ReAct agent outperforms all Reflexion baselines on BabyAI. These findings highlight the robustness and effectiveness of OmniReflect across environments and backbones.

[Arxiv](https://arxiv.org/abs/2506.17449)