# 无需参考模型的长度可控边界偏好优化

发布时间：2025年02月20日

`LLM理论` `人工智能`

> Length-Controlled Margin-Based Preference Optimization without Reference Model

# 摘要

> 直接偏好优化（DPO）是一种在基于人类反馈的强化学习（RLHF）中广泛应用的线下算法，通过重新定义奖励函数来提升训练的简便性和稳定性。然而，DPO存在长度偏见、内存低效和概率退化等局限性。为了解决这些问题，我们提出了基于长度控制和边际的偏好优化（LMPO），这是一种更高效和鲁棒的替代方案。

LMPO通过引入一个统一的参考模型作为DPO损失函数的上限，能够更准确地逼近原始优化目标。同时，我们采用平均对数概率优化策略，以减少训练阶段与推理阶段之间的差异。LMPO的核心创新在于其基于长度控制和边际的损失函数，该函数集成在Bradley-Terry框架中。这一损失函数不仅能够调控响应长度，还能扩大优选输出与拒绝输出之间的边际距离。通过这种方式，LMPO有效缓解了被接受和被丢弃响应的概率退化问题，克服了现有方法的关键局限性。

我们在开源大型语言模型Mistral和LLaMA3上，针对六项条件基准测试，将LMPO与最先进的偏好优化技术进行了对比评估。实验结果表明，LMPO在控制响应长度、减少概率退化以及整体性能上均优于现有方法。代码可从url{https://github.com/gengxuli/LMPO}获取。

> Direct Preference Optimization (DPO) is a widely adopted offline algorithm for preference-based reinforcement learning from human feedback (RLHF), designed to improve training simplicity and stability by redefining reward functions. However, DPO is hindered by several limitations, including length bias, memory inefficiency, and probability degradation. To address these challenges, we propose Length-Controlled Margin-Based Preference Optimization (LMPO), a more efficient and robust alternative. LMPO introduces a uniform reference model as an upper bound for the DPO loss, enabling a more accurate approximation of the original optimization objective. Additionally, an average log-probability optimization strategy is employed to minimize discrepancies between training and inference phases. A key innovation of LMPO lies in its Length-Controlled Margin-Based loss function, integrated within the Bradley-Terry framework. This loss function regulates response length while simultaneously widening the margin between preferred and rejected outputs. By doing so, it mitigates probability degradation for both accepted and discarded responses, addressing a significant limitation of existing methods. We evaluate LMPO against state-of-the-art preference optimization techniques on two open-ended large language models, Mistral and LLaMA3, across six conditional benchmarks. Our experimental results demonstrate that LMPO effectively controls response length, reduces probability degradation, and outperforms existing approaches. The code is available at \url{https://github.com/gengxuli/LMPO}.

[Arxiv](https://arxiv.org/abs/2502.14643)