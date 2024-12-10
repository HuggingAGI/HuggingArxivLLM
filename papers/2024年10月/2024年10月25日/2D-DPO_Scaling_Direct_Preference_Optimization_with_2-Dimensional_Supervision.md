# 2D-DPO：借助二维监督实现直接偏好优化的扩展

发布时间：2024年10月25日

`LLM应用` `语言模型` `偏好优化`

> 2D-DPO: Scaling Direct Preference Optimization with 2-Dimensional Supervision

# 摘要

> 近期，直接偏好优化（DPO）的新进展因其简单高效，显著提升了大型语言模型（LLMs）与人类偏好的契合度。然而，现有的方法往往只优化标量分数或排名奖励，忽略了人类偏好的多维特性。在本研究中，我们提议将 DPO 的偏好拓展至二维：片段和方面。我们首先引入了名为 HelpSteer-2D 的二维监督数据集。就片段维度而言，我们把响应划分为句子，并给每个片段打分。针对方面维度，我们精心设计了涵盖响应质量准则的若干标准。以二维信号作为反馈，我们构建了一个 2D-DPO 框架，将整体目标分解为多片段和多方面的目标。在热门基准上的大量实验表明，2D-DPO 比优化标量或一维偏好的方法表现更优。

> Recent advancements in Direct Preference Optimization (DPO) have significantly enhanced the alignment of Large Language Models (LLMs) with human preferences, owing to its simplicity and effectiveness. However, existing methods typically optimize a scalar score or ranking reward, thereby overlooking the multi-dimensional nature of human preferences. In this work, we propose to extend the preference of DPO to two dimensions: segments and aspects. We first introduce a 2D supervision dataset called HelpSteer-2D. For the segment dimension, we divide the response into sentences and assign scores to each segment. For the aspect dimension, we meticulously design several criteria covering the response quality rubrics. With the 2-dimensional signals as feedback, we develop a 2D-DPO framework, decomposing the overall objective into multi-segment and multi-aspect objectives. Extensive experiments on popular benchmarks demonstrate that 2D-DPO performs better than methods that optimize for scalar or 1-dimensional preferences.

[Arxiv](https://arxiv.org/abs/2410.19720)