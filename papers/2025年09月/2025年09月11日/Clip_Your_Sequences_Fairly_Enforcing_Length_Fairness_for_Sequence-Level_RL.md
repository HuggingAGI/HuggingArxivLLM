# 公平裁剪序列：强化序列级强化学习的长度公平性

发布时间：2025年09月11日

`强化学习` `基础理论`

> Clip Your Sequences Fairly: Enforcing Length Fairness for Sequence-Level RL

# 摘要

> 我们提出FSPO（公平序列策略优化）——一种面向大型语言模型（LLMs）的序列级强化学习方法，可直接在重要性采样（IS）权重空间中实现长度公平裁剪。重新审视序列级强化学习方法后我们发现，将PPO/GRPO风格的裁剪应用于序列时存在适配问题：固定裁剪范围会系统性地改变长短响应的权重，进而扭曲实际优化目标。理论层面，我们借助长度重加权误差（LRE）对长度公平性进行形式化定义，并证明较小的LRE可确保裁剪更新与真实更新之间的方向余弦特性。FSPO为此提出一种简洁的高斯启发式解决方案：通过一个包含KL校正漂移项且按【数学公式】缩放的区间，对序列对数IS比率进行裁剪。实证结果表明，FSPO能拉平不同长度区间的裁剪率，稳定训练过程，且在多个评估数据集上性能均优于所有基线模型。

> We propose FSPO (Fair Sequence Policy Optimization), a sequence-level reinforcement learning method for LLMs that enforces length-fair clipping directly in the importance-sampling (IS) weight space. We revisit sequence-level RL methods and identify a mismatch when PPO/GRPO-style clipping is transplanted to sequences: a fixed clip range systematically reweights short vs. long responses, distorting the effective objective. Theoretically, we formalize length fairness via a Length Reweighting Error (LRE) and prove that small LRE yields a directional cosine guarantee between the clipped and true updates. FSPO introduces a simple, Gaussian-motivated remedy: we clip the sequence log-IS ratio with a band that applies a KL-corrected drift term and scales as $\sqrt{L}$. Empirically, FSPO flattens clip rates across length bins, stabilizes training, and outperforms all baselines across multiple evaluation datasets.

[Arxiv](https://arxiv.org/abs/2509.09177)