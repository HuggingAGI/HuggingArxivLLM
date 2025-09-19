# 关注差距：面向稳定离策略监督微调的数据重写

发布时间：2025年09月18日

`强化学习` `基础理论`

> Mind the Gap: Data Rewriting for Stable Off-Policy Supervised Fine-Tuning

# 摘要

> 大型语言模型的监督微调（SFT）可视为异策略学习问题：专家演示来自固定的行为策略，而训练目标则是优化目标策略。重要性采样是纠正此类分布不匹配的标准方法，但较大的策略差距会引发高方差与训练不稳定。现有方法通过KL散度惩罚或裁剪来缓解这一问题，然而这些方法只是被动约束更新，而非主动缩小差距。为此，我们提出一种简洁高效的数据重写框架：将正确解保留为同策略数据，对错误解进行引导式重新求解并重写，仅在必要时才退回到专家演示，以此主动缩小策略差距。该框架能在优化前让训练分布与目标策略对齐，从而降低重要性采样方差，稳定异策略微调过程。在五个数学推理基准测试上的实验结果显示，相较于基础SFT和最先进的动态微调（DFT）方法，我们的方法实现了持续且显著的性能提升。相关数据与代码将发布于https://github.com/NKU-HLT/Off-Policy-SFT。

> Supervised fine-tuning (SFT) of large language models can be viewed as an off-policy learning problem, where expert demonstrations come from a fixed behavior policy while training aims to optimize a target policy. Importance sampling is the standard tool for correcting this distribution mismatch, but large policy gaps lead to high variance and training instability. Existing approaches mitigate this issue using KL penalties or clipping, which passively constrain updates rather than actively reducing the gap. We propose a simple yet effective data rewriting framework that proactively shrinks the policy gap by keeping correct solutions as on-policy data and rewriting incorrect ones with guided re-solving, falling back to expert demonstrations only when needed. This aligns the training distribution with the target policy before optimization, reducing importance sampling variance and stabilizing off-policy fine-tuning. Experiments on five mathematical reasoning benchmarks demonstrate consistent and significant gains over both vanilla SFT and the state-of-the-art Dynamic Fine-Tuning (DFT) approach. The data and code will be released at https://github.com/NKU-HLT/Off-Policy-SFT.

[Arxiv](https://arxiv.org/abs/2509.15157)