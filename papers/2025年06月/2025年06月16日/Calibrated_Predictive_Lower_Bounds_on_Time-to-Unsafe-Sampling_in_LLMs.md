# 大型语言模型中不安全采样时间的校准预测下限

发布时间：2025年06月16日

`LLM应用` `生成式AI` `模型安全`

> Calibrated Predictive Lower Bounds on Time-to-Unsafe-Sampling in LLMs

# 摘要

> 我们开发了一个框架，用于量化触发不安全响应所需的LLM生成次数，即到达不安全采样的时间。由于不安全响应在良好对齐的LLM中极为罕见，准确估计这一数值极具挑战性，可能需要数千次生成才能出现一次不安全响应。直接估计到达不安全采样的时间需要收集大量生成数据，这在计算上不可行。在现实的采样预算下，我们通常无法为每个提示生成足够的响应以观察到不安全结果，导致在许多情况下无法观测到到达不安全采样的时间，使得估计和评估任务尤为具有挑战性。

为了解决这一问题，我们将此估计问题视为生存分析问题，并利用近期在符合性预测方面的进展，为给定提示的到达不安全采样时间开发了一个可证明的校准下界预测（LPB）。我们的关键创新在于设计了一种自适应的、按提示的采样策略，将其形式化为一个凸优化问题。指导这一优化采样分配的目标函数旨在减少用于构建LPB的估计量的方差，从而在统计效率上超越每提示固定采样预算的简单方法。

在合成数据和真实数据上的实验支持了我们的理论结果，并展示了我们方法在生成式AI模型安全风险评估中的实际效用。

> We develop a framework to quantify the time-to-unsafe-sampling - the number of large language model (LLM) generations required to trigger an unsafe (e.g., toxic) response. Estimating this quantity is challenging, since unsafe responses are exceedingly rare in well-aligned LLMs, potentially occurring only once in thousands of generations. As a result, directly estimating time-to-unsafe-sampling would require collecting training data with a prohibitively large number of generations per prompt. However, with realistic sampling budgets, we often cannot generate enough responses to observe an unsafe outcome for every prompt, leaving the time-to-unsafe-sampling unobserved in many cases, making the estimation and evaluation tasks particularly challenging. To address this, we frame this estimation problem as one of survival analysis and develop a provably calibrated lower predictive bound (LPB) on the time-to-unsafe-sampling of a given prompt, leveraging recent advances in conformal prediction. Our key innovation is designing an adaptive, per-prompt sampling strategy, formulated as a convex optimization problem. The objective function guiding this optimized sampling allocation is designed to reduce the variance of the estimators used to construct the LPB, leading to improved statistical efficiency over naive methods that use a fixed sampling budget per prompt. Experiments on both synthetic and real data support our theoretical results and demonstrate the practical utility of our method for safety risk assessment in generative AI models.

[Arxiv](https://arxiv.org/abs/2506.13593)