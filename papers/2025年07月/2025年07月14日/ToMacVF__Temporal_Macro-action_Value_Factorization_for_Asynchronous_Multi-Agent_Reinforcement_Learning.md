# ToMacVF：异步多智能体强化学习中的时序宏动作价值分解方法

发布时间：2025年07月14日

`Agent` `机器人学` `多智能体系统`

> ToMacVF : Temporal Macro-action Value Factorization for Asynchronous Multi-Agent Reinforcement Learning

# 摘要

> 现有的基于MacDec-POMDP的异步MARL方法通常通过在宏观动作的端点简单地采样有限且有偏的数据来构建训练轨迹缓存，并直接在缓存上应用传统的MARL方法。这导致了宏观动作执行过程的不完整和不准确表示，以及不合适的信用分配。为了解决这些问题，我们提出了时间宏观动作值分解（ToMacVF），以实现宏观动作贡献的精细时间信用分配。设计了一个称为宏观动作分段联合经验回放轨迹（Mac-SJERT）的集中式训练缓存，与ToMacVF结合使用，以收集准确和完整的宏观动作执行信息，支持对宏观动作过程的更全面和精确的表示。为了确保原理性和精细的异步值分解，正式化了联合和个体宏观动作选择之间的一致性要求，称为基于时间宏观动作的IGM（To-Mac-IGM），证明了它概括了同步情况。基于To-Mac-IGM，设计了一个模块化的满足CTDE原则的ToMacVF架构，以便方便地集成以前的价值分解方法。接下来，设计了ToMacVF算法作为ToMacVF架构的实现。实验结果表明，与异步基线相比，我们的ToMacVF算法不仅实现了最优性能，还在各种异步多智能体实验场景中表现出强大的适应性和鲁棒性。

> Existing asynchronous MARL methods based on MacDec-POMDP typically construct training trajectory buffers by simply sampling limited and biased data at the endpoints of macro-actions, and directly apply conventional MARL methods on the buffers. As a result, these methods lead to an incomplete and inaccurate representation of the macro-action execution process, along with unsuitable credit assignments. To solve these problems, the Temporal Macro-action Value Factorization (ToMacVF) is proposed to achieve fine-grained temporal credit assignment for macro-action contributions. A centralized training buffer, called Macro-action Segmented Joint Experience Replay Trajectory (Mac-SJERT), is designed to incorporate with ToMacVF to collect accurate and complete macro-action execution information, supporting a more comprehensive and precise representation of the macro-action process. To ensure principled and fine-grained asynchronous value factorization, the consistency requirement between joint and individual macro-action selection called Temporal Macro-action based IGM (To-Mac-IGM) is formalized, proving that it generalizes the synchronous cases. Based on To-Mac-IGM, a modularized ToMacVF architecture, which satisfies CTDE principle, is designed to conveniently integrate previous value factorization methods. Next, the ToMacVF algorithm is devised as an implementation of the ToMacVF architecture. Experimental results demonstrate that, compared to asynchronous baselines, our ToMacVF algorithm not only achieves optimal performance but also exhibits strong adaptability and robustness across various asynchronous multi-agent experimental scenarios.

[Arxiv](https://arxiv.org/abs/2507.10251)