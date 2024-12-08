# SAUP：关于 LLM 代理的态势感知不确定性传播

发布时间：2024年12月01日

`Agent` `决策系统` `不确定性估计`

> SAUP: Situation Awareness Uncertainty Propagation on LLM Agent

# 摘要

> 大型语言模型（LLMs）融入多步骤代理系统，能在各类应用中促成复杂的决策流程。然而，其输出常常可靠性不足，这就让不确定性估计变得极为关键。现有的不确定性估计方法多聚焦于最终步骤的输出，无法涵盖多步骤决策过程中的累积不确定性以及代理与环境间的动态交互。为应对这些局限，我们提出了 SAUP（情境感知不确定性传播）这一全新框架，它能在基于 LLM 的代理推理过程的每一步传播不确定性。SAUP 在传播过程中为每一步的不确定性赋予情境权重，从而融入情境感知。我们的方法与各种单步不确定性估计技术兼容，提供了全面且精准的不确定性衡量。在基准数据集上开展的大量实验表明，SAUP 显著优于现有的前沿方法，在 AUROC 方面提升高达 20％。

> Large language models (LLMs) integrated into multistep agent systems enable complex decision-making processes across various applications. However, their outputs often lack reliability, making uncertainty estimation crucial. Existing uncertainty estimation methods primarily focus on final-step outputs, which fail to account for cumulative uncertainty over the multistep decision-making process and the dynamic interactions between agents and their environments. To address these limitations, we propose SAUP (Situation Awareness Uncertainty Propagation), a novel framework that propagates uncertainty through each step of an LLM-based agent's reasoning process. SAUP incorporates situational awareness by assigning situational weights to each step's uncertainty during the propagation. Our method, compatible with various one-step uncertainty estimation techniques, provides a comprehensive and accurate uncertainty measure. Extensive experiments on benchmark datasets demonstrate that SAUP significantly outperforms existing state-of-the-art methods, achieving up to 20% improvement in AUROC.

[Arxiv](https://arxiv.org/abs/2412.01033)