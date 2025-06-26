# OmniReflect：通过神经符号反射发现 LLM 代理的可迁移框架

发布时间：2025年06月20日

`Agent

摘要中讨论了如何提升LLM代理的性能和效率，特别是通过反思机制和宪法构建，属于代理的行为和学习机制，因此归类到Agent。` `人工智能` `机器学习`

> OmniReflect: Discovering Transferable Constitutions for LLM agents via Neuro-Symbolic Reflections

# 摘要

> 大语言模型（LLM）代理在复杂任务中的性能提升主要依赖于微调和迭代自我修正。然而，这些方法通常缺乏通用的长期学习机制，且在动态环境中效率低下。我们提出了OmniReflect，一个层次化的、基于反思的框架，通过构建一部宪法——从任务经验中提炼出的一组简洁的指导原则——来提升LLM代理的有效性和效率。OmniReflect采用两种模式运行：自我维持模式，即单一代理在任务执行过程中定期整理自身的反思；合作模式，即Meta顾问从少量校准集中提取一部宪法来指导另一个代理。为了构建这些宪法原则，我们采用了神经、符号和神经符号技术，实现了情境适应性与计算效率之间的平衡。实验结果显示，OmniReflect在自我维持模式下显著提升了任务成功率，具体表现为ALFWorld上的绝对提升+10.3%，BabyAI上的+23.8%，以及PDDL上的+8.3%。在合作模式下，轻量级的Qwen3-4B ReAct代理在BabyAI上超越了所有Reflexion基线。这些结果凸显了OmniReflect在不同环境和模型中的鲁棒性和有效性。

> Efforts to improve Large Language Model (LLM) agent performance on complex tasks have largely focused on fine-tuning and iterative self-correction. However, these approaches often lack generalizable mechanisms for longterm learning and remain inefficient in dynamic environments. We introduce OmniReflect, a hierarchical, reflection-driven framework that constructs a constitution, a compact set of guiding principles distilled from task experiences, to enhance the effectiveness and efficiency of an LLM agent. OmniReflect operates in two modes: Self-sustaining, where a single agent periodically curates its own reflections during task execution, and Co-operative, where a Meta-advisor derives a constitution from a small calibration set to guide another agent. To construct these constitutional principles, we employ Neural, Symbolic, and NeuroSymbolic techniques, offering a balance between contextual adaptability and computational efficiency. Empirical results averaged across models show major improvements in task success, with absolute gains of +10.3% on ALFWorld, +23.8% on BabyAI, and +8.3% on PDDL in the Self-sustaining mode. Similar gains are seen in the Co-operative mode, where a lightweight Qwen3-4B ReAct agent outperforms all Reflexion baselines on BabyAI. These findings highlight the robustness and effectiveness of OmniReflect across environments and backbones.

[Arxiv](https://arxiv.org/abs/2506.17449)