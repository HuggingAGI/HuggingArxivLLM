# 基于智能体模型中潜状态估计的数据同化与基于似然推断的比较

发布时间：2025年09月22日

`Agent` `基础理论`

> Comparing Data Assimilation and Likelihood-Based Inference on Latent State Estimation in Agent-Based Models

# 摘要

> 本文首次系统比较了基于主体模型（ABMs）中的数据同化（DA）与基于似然推断（LBI）。这类模型通过演化的部分潜在微观状态生成可观测时间序列，而为使模拟贴合真实数据，需对潜在状态进行估计——这一任务传统上由DA完成，尤其适用于天气预报等连续型、基于方程的模型。但ABMs的特性给标准DA方法带来了挑战，解决这些问题需调整现有DA技术，或采用LBI等特定替代方案。DA以模型无关的方式近似似然，虽适用性广但精度可能不足；相比之下，LBI通过直接利用模型似然实现更精准的状态估计，但需手工构建特定于模型的似然函数，而这一过程可能复杂甚至难以实现。

我们在有界置信模型（一种经典的意见动态ABM）上对两种方法展开对比——在该模型中，主体仅受观点足够相似的其他主体影响。结果显示，即便存在模型误设，LBI仍能更准确地还原潜在的主体级观点，进而提升个体级预测效果。但在聚合层面，两种方法性能接近；在特定参数配置下，DA在聚合层面依旧表现出竞争力。研究结果表明：DA适用于聚合预测，LBI则更适合主体级推断。

> In this paper, we present the first systematic comparison of Data Assimilation (DA) and Likelihood-Based Inference (LBI) in the context of Agent-Based Models (ABMs). These models generate observable time series driven by evolving, partially-latent microstates. Latent states need to be estimated to align simulations with real-world data -- a task traditionally addressed by DA, especially in continuous and equation-based models such as those used in weather forecasting. However, the nature of ABMs poses challenges for standard DA methods. Solving such issues requires adaptation of previous DA techniques, or ad-hoc alternatives such as LBI. DA approximates the likelihood in a model-agnostic way, making it broadly applicable but potentially less precise. In contrast, LBI provides more accurate state estimation by directly leveraging the model's likelihood, but at the cost of requiring a hand-crafted, model-specific likelihood function, which may be complex or infeasible to derive. We compare the two methods on the Bounded-Confidence Model, a well-known opinion dynamics ABM, where agents are affected only by others holding sufficiently similar opinions. We find that LBI better recovers latent agent-level opinions, even under model mis-specification, leading to improved individual-level forecasts. At the aggregate level, however, both methods perform comparably, and DA remains competitive across levels of aggregation under certain parameter settings. Our findings suggest that DA is well-suited for aggregate predictions, while LBI is preferable for agent-level inference.

[Arxiv](https://arxiv.org/abs/2509.17625)