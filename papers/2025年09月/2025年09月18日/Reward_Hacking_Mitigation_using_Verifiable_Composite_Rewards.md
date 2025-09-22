# # 基于可验证复合奖励的奖励攻击缓解

发布时间：2025年09月18日

`强化学习` `医疗健康`

> Reward Hacking Mitigation using Verifiable Composite Rewards

# 摘要

> 可验证奖励强化学习（RLVR）近期研究显示，大型语言模型（LLMs）无需直接监督就能自主发展推理能力。然而，在医疗领域（尤其是问答场景）的应用中，模型在推理阶段极易出现严重的奖励欺骗问题。我们的研究针对这类行为的两种主要表现形式展开：i）未给出前置推理就直接输出最终答案；ii）采用非标准推理格式来钻奖励机制的空子。为缓解上述问题，我们提出了一种复合奖励函数，专门针对这些行为设置惩罚机制。实验结果显示，将RLVR与我们提出的奖励模型相结合后，相较于基线模型，推理格式更规范，奖励欺骗现象减少，且准确性表现良好。该方法为减少奖励欺骗、提升RLVR模型的可靠性奠定了基础。

> Reinforcement Learning from Verifiable Rewards (RLVR) has recently shown that large language models (LLMs) can develop their own reasoning without direct supervision. However, applications in the medical domain, specifically for question answering, are susceptible to significant reward hacking during the reasoning phase. Our work addresses two primary forms of this behavior: i) providing a final answer without preceding reasoning, and ii) employing non-standard reasoning formats to exploit the reward mechanism. To mitigate these, we introduce a composite reward function with specific penalties for these behaviors. Our experiments show that extending RLVR with our proposed reward model leads to better-formatted reasoning with less reward hacking and good accuracy compared to the baselines. This approach marks a step toward reducing reward hacking and enhancing the reliability of models utilizing RLVR.

[Arxiv](https://arxiv.org/abs/2509.15557)