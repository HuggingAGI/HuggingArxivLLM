# 面向RLVR的基于监督学习框架的隐式演员-评论家耦合

发布时间：2025年09月02日

`强化学习` `基础理论`

> Implicit Actor Critic Coupling via a Supervised Learning Framework for RLVR

# 摘要

> 强化学习与可验证奖励（RLVR）的最新进展，让大型语言模型（LLMs）能够应对数学、编程等挑战性推理任务。RLVR借助可验证的结果奖励指导策略优化，使LLMs得以扎实可靠地逐步提升输出质量。尽管前景广阔，RLVR范式仍面临重大挑战：现有方法常受稀疏奖励信号和不稳定策略梯度更新的困扰，尤其在基于RL的方法中。为应对这些挑战，我们提出【数学公式】PACS——一种新颖的RLVR框架，通过监督学习框架实现隐式Actor-Critic耦合。我们将结果奖励视作可预测标签，把RLVR问题转化为基于分数函数的监督学习任务，该分数函数由策略模型参数化并采用交叉熵损失优化。梯度分析表明，这种监督式表述在隐式耦合演员与评论家角色的同时，本质上还原了经典策略梯度更新，从而实现更稳定高效的训练。在挑战性数学推理任务的基准测试中，PACS性能超越PPO、GRPO等强RLVR基线，展现出更优推理能力。例如，在AIME 2025数据集上，PACS的pass@256指标达59.78%，较PPO和GRPO分别提升13.32和14.36个百分点。这一简洁而强大的框架，为LLMs的可验证奖励后训练开辟了新的前景。我们的代码和数据已开源，地址为https://github.com/ritzz-ai/PACS。

> Recent advances in Reinforcement Learning with Verifiable Rewards (RLVR) have empowered large language models (LLMs) to tackle challenging reasoning tasks such as mathematics and programming. RLVR leverages verifiable outcome rewards to guide policy optimization, enabling LLMs to progressively improve output quality in a grounded and reliable manner. Despite its promise, the RLVR paradigm poses significant challenges, as existing methods often suffer from sparse reward signals and unstable policy gradient updates, particularly in RL-based approaches. To address the challenges, we propose $\textbf{PACS}$, a novel RLVR framework that achieves im$\textbf{P}$licit $\textbf{A}$ctor $\textbf{C}$ritic coupling via a $\textbf{S}$upervised learning framework. By treating the outcome reward as a predictable label, we reformulate the RLVR problem into a supervised learning task over a score function parameterized by the policy model and optimized using cross-entropy loss. A detailed gradient analysis shows that this supervised formulation inherently recovers the classical policy gradient update while implicitly coupling actor and critic roles, yielding more stable and efficient training. Benchmarking on challenging mathematical reasoning tasks, PACS outperforms strong RLVR baselines, such as PPO and GRPO, achieving superior reasoning performance. For instance, PACS achieves 59.78\% at pass@256 on AIME 2025, representing improvements of 13.32 and 14.36 points over PPO and GRPO. This simple yet powerful framework offers a promising avenue for LLMs post-training with verifiable rewards. Our code and data are available as open source at https://github.com/ritzz-ai/PACS.

[Arxiv](https://arxiv.org/abs/2509.02522)