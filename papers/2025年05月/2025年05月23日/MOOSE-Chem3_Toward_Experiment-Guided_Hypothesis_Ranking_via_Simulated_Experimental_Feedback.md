# MOOSE-Chem3：通过模拟实验反馈实现实验引导的假设排序

发布时间：2025年05月23日

`LLM应用` `科学自动化` `数据科学`

> MOOSE-Chem3: Toward Experiment-Guided Hypothesis Ranking via Simulated Experimental Feedback

# 摘要

> 假设排序在自动化科学研究中扮演着关键角色，尤其在自然科学研究中，湿实验室实验成本高昂且吞吐量有限。现有方法主要集中在实验前排序，仅依赖大型语言模型的内部推理，未结合实验结果。我们提出了实验引导排序任务，旨在根据先前测试结果优先排序候选假设。然而，开发此类策略在自然科学研究领域面临挑战，因反复进行真实实验不切实际。为解决此问题，我们提出一个基于三个领域假设的模拟器，将假设性能建模为与已知真实假设相似度的函数，并受噪声干扰。我们整理了一个包含124个化学假设的数据集，这些假设具有实验报告结果，用于验证模拟器。基于此模拟器，我们开发了一种伪实验引导排序方法，根据共享的功能特性对假设进行聚类，并根据模拟实验反馈的见解优先排序候选假设。实验表明，我们的方法优于实验前基线和强对比方法。


> Hypothesis ranking is a crucial component of automated scientific discovery, particularly in natural sciences where wet-lab experiments are costly and throughput-limited. Existing approaches focus on pre-experiment ranking, relying solely on large language model's internal reasoning without incorporating empirical outcomes from experiments. We introduce the task of experiment-guided ranking, which aims to prioritize candidate hypotheses based on the results of previously tested ones. However, developing such strategies is challenging due to the impracticality of repeatedly conducting real experiments in natural science domains. To address this, we propose a simulator grounded in three domain-informed assumptions, modeling hypothesis performance as a function of similarity to a known ground truth hypothesis, perturbed by noise. We curate a dataset of 124 chemistry hypotheses with experimentally reported outcomes to validate the simulator. Building on this simulator, we develop a pseudo experiment-guided ranking method that clusters hypotheses by shared functional characteristics and prioritizes candidates based on insights derived from simulated experimental feedback. Experiments show that our method outperforms pre-experiment baselines and strong ablations.

[Arxiv](https://arxiv.org/abs/2505.17873)