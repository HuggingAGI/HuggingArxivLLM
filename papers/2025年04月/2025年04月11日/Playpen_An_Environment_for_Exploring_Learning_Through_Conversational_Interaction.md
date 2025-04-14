# # Playpen：对话驱动学习探索的环境

发布时间：2025年04月11日

`LLM理论` `对话生成`

> Playpen: An Environment for Exploring Learning Through Conversational Interaction

# 摘要

> 学习信号是否即将耗尽？在大规模文本中预测下一个词已被证明是强大的学习信号，但目前迹象表明，这一资源正在逐渐枯竭。最近，学习者与反馈提供者之间的互动成为焦点，这不仅关乎“对齐”（奖励模型评估指令质量），也关乎提升“推理”能力（基于过程和结果的验证器评估推理步骤）。本文探讨了我们在“对话游戏”中合成交互能提供多强的学习信号，以及如何有效利用这一信号。我们介绍了一个用于生成此类交互数据的环境（借助大型语言模型作为学习模型的对手），支持线上线下两种模式。我们研究了监督微调对这些数据的影响，以及DPO和GRPO等强化学习设置。结果显示，所有方法在域内游戏中均有改进，但只有GRPO展示了泛化到域外游戏以及在基于参考的任务中保持竞争力的能力。我们公开了框架和基线训练设置，以期推动这一有潜力新方向的研究。

> Are we running out of learning signal? Predicting the next word in an existing text has turned out to be a powerful signal, at least at scale. But there are signs that we are running out of this resource. In recent months, interaction between learner and feedback-giver has come into focus, both for "alignment" (with a reward model judging the quality of instruction following attempts) and for improving "reasoning" (process- and outcome-based verifiers judging reasoning steps). In this paper, we explore to what extent synthetic interaction in what we call Dialogue Games -- goal-directed and rule-governed activities driven predominantly by verbal actions -- can provide a learning signal, and how this signal can be used. We introduce an environment for producing such interaction data (with the help of a Large Language Model as counterpart to the learner model), both offline and online. We investigate the effects of supervised fine-tuning on this data, as well as reinforcement learning setups such as DPO, and GRPO; showing that all of these approaches achieve some improvements in in-domain games, but only GRPO demonstrates the ability to generalise to out-of-domain games as well as retain competitive performance in reference-based tasks. We release the framework and the baseline training setups in the hope that this can foster research in this promising new direction.

[Arxiv](https://arxiv.org/abs/2504.08590)