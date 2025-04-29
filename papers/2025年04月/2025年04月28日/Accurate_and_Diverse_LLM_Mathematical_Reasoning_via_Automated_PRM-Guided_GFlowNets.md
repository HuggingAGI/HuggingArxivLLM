# 通过自动化PRM引导的生成流网络实现大型语言模型的准确且多样的数学推理能力

发布时间：2025年04月28日

`LLM应用`

> Accurate and Diverse LLM Mathematical Reasoning via Automated PRM-Guided GFlowNets

# 摘要

> 在数学等复杂领域，大型语言模型 (LLMs) 的准确性和多样化推理能力仍具挑战。关键难点在于如何在不依赖昂贵人工标注的情况下，有效评估推理步骤以指导生成。为解决这一问题，我们首先提出了一种全新的过程奖励模型 (PRM)，该模型通过蒙特卡洛树搜索结合相似性数据增强技术进行自动训练，精准捕捉推理步骤的质量。借助这一PRM，我们将生成流网络 (GFlowNets) 应用于推理步骤级别。与传统强化学习专注于最大化单一奖励不同，GFlowNets 能够自然地按奖励比例采样多样化、高质量的解决方案，这些奖励由我们的PRM衡量。实证研究表明，在具有挑战性的数学基准测试（例如 Llama3.2-3B 在 MATH Level 5 上绝对准确率提升 +2.59%）中，准确性和解决方案多样性均显著提升，并且能够有效推广到未见过的数据集（SAT MATH 上绝对提升 +9.4%）。我们的工作展示了由 PRM 引导的、基于推理步骤的 GFlowNets 在开发更强大和多样化数学推理能力方面的潜力。

> Achieving both accuracy and diverse reasoning remains challenging for Large Language Models (LLMs) in complex domains like mathematics. A key bottleneck is evaluating intermediate reasoning steps to guide generation without costly human annotations. To address this, we first introduce a novel Process Reward Model (PRM) trained automatically using Monte Carlo Tree Search coupled with a similarity-based data augmentation technique, effectively capturing step-level reasoning quality. Leveraging this PRM, we then adapt Generative Flow Networks (GFlowNets) to operate at the reasoning step level. Unlike traditional reinforcement learning focused on maximizing a single reward, GFlowNets naturally sample diverse, high-quality solutions proportional to their rewards, as measured by our PRM. Empirical evaluation shows strong improvements in both accuracy and solution diversity on challenging mathematical benchmarks (e.g., +2.59% absolute accuracy on MATH Level 5 for Llama3.2-3B), with effective generalization to unseen datasets (+9.4% absolute on SAT MATH). Our work demonstrates the potential of PRM-guided, step-level GFlowNets for developing more robust and versatile mathematical reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2504.19981)