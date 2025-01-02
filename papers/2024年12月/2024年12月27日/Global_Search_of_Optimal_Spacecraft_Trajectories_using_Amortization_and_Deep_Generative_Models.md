# 利用摊销和深度生成模型在全球范围内搜索最优航天器轨迹

发布时间：2024年12月27日

`其他` `航天器轨迹优化`

> Global Search of Optimal Spacecraft Trajectories using Amortization and Deep Generative Models

# 摘要

> 初步的航天器轨迹优化是一个依赖参数的全局搜索问题，旨在给出一组优质且多样的解决方案。就数值解而言，它取决于初始的最优控制问题、控制转录的选取以及基于梯度的数值求解器的表现。在本文里，我们把参数化的全局搜索问题设定为对支持在高质量解决方案的局部吸引盆邻域的条件概率分布进行采样的任务。这一条件分布通过深度生成模型来学习和呈现，这些模型能够预测随着参数变化局部吸引盆的变化情况。该方法在圆形受限三体问题中的低推力航天器轨迹优化问题上进行了基准测试，相比简单的多起点方法和常规机器学习方法，速度显著提升。本文还深入剖析了低推力航天器轨迹优化问题的多模态漏斗结构。

> Preliminary spacecraft trajectory optimization is a parameter dependent global search problem that aims to provide a set of solutions that are of high quality and diverse. In the case of numerical solution, it is dependent on the original optimal control problem, the choice of a control transcription, and the behavior of a gradient based numerical solver. In this paper we formulate the parameterized global search problem as the task of sampling a conditional probability distribution with support on the neighborhoods of local basins of attraction to the high quality solutions. The conditional distribution is learned and represented using deep generative models that allow for prediction of how the local basins change as parameters vary. The approach is benchmarked on a low thrust spacecraft trajectory optimization problem in the circular restricted three-body problem, showing significant speed-up over a simple multi-start method and vanilla machine learning approaches. The paper also provides an in-depth analysis of the multi-modal funnel structure of a low-thrust spacecraft trajectory optimization problem.

[Arxiv](https://arxiv.org/abs/2412.20023)