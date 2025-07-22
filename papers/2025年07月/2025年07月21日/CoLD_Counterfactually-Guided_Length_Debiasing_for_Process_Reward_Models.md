# CoLD：针对过程奖励模型的反事实引导长度去偏方法

发布时间：2025年07月21日

`LLM理论`

> CoLD: Counterfactually-Guided Length Debiasing for Process Reward Models

# 摘要

> 过程奖励模型（PRMs）在评估和指导大型语言模型（LLMs）中的多步骤推理，特别是在数学问题解决方面，扮演着核心角色。然而，我们发现现有PRMs中存在一种普遍的长度偏差：它们往往会给更长的推理步骤分配更高的分数，即使语义内容和逻辑有效性保持不变。这种偏差削弱了奖励预测的可靠性，并导致推理过程中生成过于冗长的输出。

为了解决这一问题，我们提出了CoLD（反事实引导的长度去偏框架），一个通过三个组件来缓解长度偏差的统一框架：明确的长度惩罚调整、训练以捕捉虚假长度相关信号的学习偏差估计器，以及强制奖励预测中长度不变性的联合训练策略。我们的方法基于反事实推理，并通过因果图分析获得启发。

在MATH500和GSM-Plus上的大量实验表明，CoLD一致降低了奖励与长度的相关性，提高了步骤选择的准确性，并鼓励了更加简洁且逻辑上有效的推理。这些结果证明了CoLD在提升PRMs保真度和鲁棒性方面的有效性和实用性。


> Process Reward Models (PRMs) play a central role in evaluating and guiding multi-step reasoning in large language models (LLMs), especially for mathematical problem solving. However, we identify a pervasive length bias in existing PRMs: they tend to assign higher scores to longer reasoning steps, even when the semantic content and logical validity are unchanged. This bias undermines the reliability of reward predictions and leads to overly verbose outputs during inference. To address this issue, we propose CoLD(Counterfactually-Guided Length Debiasing), a unified framework that mitigates length bias through three components: an explicit length-penalty adjustment, a learned bias estimator trained to capture spurious length-related signals, and a joint training strategy that enforces length-invariance in reward predictions. Our approach is grounded in counterfactual reasoning and informed by causal graph analysis. Extensive experiments on MATH500 and GSM-Plus show that CoLD consistently reduces reward-length correlation, improves accuracy in step selection, and encourages more concise, logically valid reasoning. These results demonstrate the effectiveness and practicality of CoLD in improving the fidelity and robustness of PRMs.

[Arxiv](https://arxiv.org/abs/2507.15698)