# 一致聊天：构建骨架引导的一致性对话系统，助力大型语言模型实现从零到一的跨越

发布时间：2025年06月04日

`LLM应用` `对话系统`

> ConsistentChat: Building Skeleton-Guided Consistent Dialogues for Large Language Models from Scratch

# 摘要

> 现有的指令数据合成方法大多专注于单轮指令，却常常忽视跨轮对话的连贯性，这导致在长对话中出现上下文漂移，影响了任务完成率。为解决这一问题，我们提出了骨架引导的多轮对话生成框架，通过显式建模人类对话意图来约束多轮指令合成过程。该框架分为两个阶段：首先，意图建模阶段将每段对话分配到九种明确定义的意图轨迹中，从而捕获人类对话的全局结构，确保信息流连贯且具有目标导向；其次，骨架生成阶段根据建模的意图构建结构化的用户查询序列，作为约束和引导下游指令合成过程的支架。基于此，我们构建了包含约15,000个多轮对话和224,392个utterances的ConsistentChat多轮指令数据集。在Light、Topdial和MT-Eval基准测试中的实验结果表明，基于ConsistentChat进行微调的模型在聊天一致性方面提升了20-30%，任务成功率提高了高达15%，显著优于基于现有单轮和多轮指令数据集训练的模型。

> Current instruction data synthesis methods primarily focus on single-turn instructions and often neglect cross-turn coherence, resulting in context drift and reduced task completion rates in extended conversations. To address this limitation, we propose Skeleton-Guided Multi-Turn Dialogue Generation, a framework that constrains multi-turn instruction synthesis by explicitly modeling human conversational intent. It operates in two stages: (1) Intent Modeling, which captures the global structure of human dialogues by assigning each conversation to one of nine well-defined intent trajectories, ensuring a coherent and goal-oriented information flow; and (2) Skeleton Generation, which constructs a structurally grounded sequence of user queries aligned with the modeled intent, thereby serving as a scaffold that constrains and guides the downstream instruction synthesis process. Based on this process, we construct ConsistentChat, a multi-turn instruction dataset with approximately 15,000 multi-turn conversations and 224,392 utterances. Experiments on the Light, Topdial, and MT-Eval benchmarks show that models fine-tuned on ConsistentChat achieve a 20-30% improvement in chat consistency and up to a 15% increase in task success rate, significantly outperforming models trained on existing single-turn and multi-turn instruction datasets.

[Arxiv](https://arxiv.org/abs/2506.03558)