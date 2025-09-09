# 结果导向的LLM推理探索

发布时间：2025年09月08日

`强化学习` `基础理论`

> Outcome-based Exploration for LLM Reasoning

# 摘要

> 强化学习（RL）已然成为提升大型语言模型（LLMs）推理能力的利器。其中，基于结果的RL仅依据最终答案的正确性对策略进行奖励——这种方式虽能显著提升准确率，却会引发生成多样性的系统性衰退。这种多样性崩溃会严重影响实际部署效果，因为多样性正是测试阶段实现规模扩展的关键。为探究这一现象，我们将RL后训练视作采样过程进行分析，结果令人惊讶：相比基础模型，RL甚至会减少训练集上的有效多样性。研究揭示了两个核心发现：（i）多样性退化的迁移效应——已解决问题的多样性降低会“传染”给未解决问题；（ii）结果空间的可驾驭性——推理任务通常只存在有限的不同答案集合。基于这些发现，我们提出了“基于结果的探索”机制——根据最终结果分配探索奖励。具体而言，我们设计了两种互补算法：历史探索（通过UCB风格的奖励机制鼓励生成罕见答案）和批次探索（通过惩罚批次内的答案重复来增强测试时的多样性）。在标准竞赛数学任务上，我们使用Llama和Qwen模型进行了实验，结果显示两种方法均能在提升准确率的同时有效缓解多样性崩溃。理论层面，我们通过提出一种新的“基于结果的老虎机”模型，对基于结果探索的优势进行了形式化分析。这些成果共同为RL方法开辟了一条实用路径：在不牺牲可扩展部署所需多样性的前提下，有效增强模型的推理能力。

> Reinforcement learning (RL) has emerged as a powerful method for improving the reasoning abilities of large language models (LLMs). Outcome-based RL, which rewards policies solely for the correctness of the final answer, yields substantial accuracy gains but also induces a systematic loss in generation diversity. This collapse undermines real-world performance, where diversity is critical for test-time scaling. We analyze this phenomenon by viewing RL post-training as a sampling process and show that, strikingly, RL can reduce effective diversity even on the training set relative to the base model. Our study highlights two central findings: (i) a transfer of diversity degradation, where reduced diversity on solved problems propagates to unsolved ones, and (ii) the tractability of the outcome space, since reasoning tasks admit only a limited set of distinct answers. Motivated by these insights, we propose outcome-based exploration, which assigns exploration bonuses according to final outcomes. We introduce two complementary algorithms: historical exploration, which encourages rarely observed answers via UCB-style bonuses, and batch exploration, which penalizes within-batch repetition to promote test-time diversity. Experiments on standard competition math with Llama and Qwen models demonstrate that both methods improve accuracy while mitigating diversity collapse. On the theoretical side, we formalize the benefit of outcome-based exploration through a new model of outcome-based bandits. Together, these contributions chart a practical path toward RL methods that enhance reasoning without sacrificing the diversity essential for scalable deployment.

[Arxiv](https://arxiv.org/abs/2509.06941)