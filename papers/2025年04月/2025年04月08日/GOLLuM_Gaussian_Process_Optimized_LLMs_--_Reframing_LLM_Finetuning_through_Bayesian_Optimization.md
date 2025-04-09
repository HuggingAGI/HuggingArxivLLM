# # **GOLLuM: 基于高斯过程优化的LLMs -- 通过贝叶斯优化重新定义LLM微调**

发布时间：2025年04月08日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在不确定性优化中的应用，特别是通过与高斯过程（GP）结合，提升优化效率。研究展示了LLMs在实际任务中的应用效果，属于应用层面的研究。` `分子属性优化`

> GOLLuM: Gaussian Process Optimized LLMs -- Reframing LLM Finetuning through Bayesian Optimization

# 摘要

> 大型语言模型（LLMs）能够在潜在空间中编码复杂的关系，但如何利用它们进行不确定性优化仍具挑战。我们提出了一种新型架构，通过深度核方法将LLM微调重新定义为高斯过程（GP）边缘似然优化。我们引入了基于LLM的深度核函数，与GP联合优化，以保留两者的优点：LLMs为贝叶斯优化提供丰富灵活的输入空间，而GP则通过预测不确定性对这一空间进行建模，从而实现更高效的采样。在Buchwald-Hartwig反应优化中，与静态LLM嵌入相比，我们的方法将高性能反应的发现率几乎翻倍（在50次优化迭代中，覆盖前5%反应的范围从24%提升至43%）。与领域特定表示相比，我们还观察到14%的改进，而无需任何专用特征。在涵盖从一般化学到反应和分子属性优化的19个基准测试中，我们方法的鲁棒性、通用性和一致性得到了广泛实证验证：（1）任务，（2）LLM架构（编码器、解码器、编码器-解码器），（3）预训练领域（与化学相关或通用），以及（4）超参数设置（在单个数据集上进行一次调优）。最后，我们解释了这些改进：通过边缘似然的联合LLM-GP优化隐式执行对比学习，使表示对齐以实现（1）结构更优的嵌入空间，（2）改进的不确定性校准，以及（3）更高效的采样——无需任何外部损失。这项工作在样本高效的优化方面取得了实用进展，并揭示了有效贝叶斯优化的关键因素。

> Large Language Models (LLMs) can encode complex relationships in their latent spaces, yet harnessing them for optimization under uncertainty remains challenging. We address this gap with a novel architecture that reframes LLM finetuning as Gaussian process (GP) marginal likelihood optimization via deep kernel methods. We introduce LLM-based deep kernels, jointly optimized with GPs to preserve the benefits of both - LLMs to provide a rich and flexible input space for Bayesian optimization and - GPs to model this space with predictive uncertainty for more efficient sampling. Applied to Buchwald-Hartwig reaction optimization, our method nearly doubles the discovery rate of high-performing reactions compared to static LLM embeddings (from 24% to 43% coverage of the top 5% reactions in just 50 optimization iterations). We also observe a 14% improvement over domain-specific representations without requiring specialized features. Extensive empirical evaluation across 19 benchmarks - ranging from general chemistry to reaction and molecular property optimization - demonstrates our method's robustness, generality, and consistent improvements across: (1) tasks, (2) LLM architectures (encoder, decoder, encoder-decoder), (3) pretraining domains (chemistry-related or general-purpose) and (4) hyperparameter settings (tuned once on a single dataset). Finally, we explain these improvements: joint LLM-GP optimization through marginal likelihood implicitly performs contrastive learning, aligning representations to produce (1) better-structured embedding spaces, (2) improved uncertainty calibration, and (3) more efficient sampling - without requiring any external loss. This work provides both practical advances in sample-efficient optimization and insights into what makes effective Bayesian optimization.

[Arxiv](https://arxiv.org/abs/2504.06265)