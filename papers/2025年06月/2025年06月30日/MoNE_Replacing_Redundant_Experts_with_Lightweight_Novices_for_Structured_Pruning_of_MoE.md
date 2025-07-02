# MoNE：通过轻量级新手替代冗余专家实现MoE的结构化剪枝

发布时间：2025年06月30日

`LLM理论` `机器学习`

> MoNE: Replacing Redundant Experts with Lightweight Novices for Structured Pruning of MoE

# 摘要

> 混合专家模型（MoE）让大型语言模型的扩展更加高效，只需激活每个输入标记的一小部分专家。然而，部署基于MoE的模型会带来显著的内存开销，因为需要将所有专家保留在内存中。虽然结构化剪枝有望降低内存成本，但现有方法在模型架构、校准数据来源和校准样本数量三个维度上，往往表现不佳且退化不稳定。本文提出了一种名为“新手与专家混合模型”（MoNE）的新颖专家剪枝方法，通过用轻量级新手替换冗余专家，实现有效且稳健的模型压缩。MoNE基于两个指标评估专家冗余：访问频率和输出方差。那些使用率低且输出稳定的专家将被剪枝，并替换为轻量级新手——对其原始输出的无偏估计，从而最小化性能退化。大量实验表明，MoNE在三个维度上均优于基线方法，且准确率退化最小，证实了其有效性和稳健性。值得注意的是，在25%和50%的剪枝比率下，MoNE分别将九项下游任务的平均零样本准确率提升了【数学公式】和【数学公式】。代码可在"https://github.com/zxgx/mode-pd"获取。

> Mixture-of-Experts (MoE) enables efficient scaling of large language models by activating only a subset of experts per input token. However, deploying MoE-based models incurs significant memory overhead due to the need to retain all experts in memory. While structured pruning is promising to reduce memory costs, existing methods often show suboptimal performance and unstable degradation in three dimensions: model architectures, calibration data sources, and calibration sample sizes. This paper proposes Mixture-of-Novices-and-Experts (MoNE), a novel expert pruning method that replaces redundant experts with lightweight novices to achieve effective and robust model compression. MoNE evaluates expert redundancy based on two metrics: access frequency and output variance. Experts exhibiting low usage and stable outputs are pruned and replaced with lightweight novices-unbiased estimations of their original outputs-minimizing performance degradation. Extensive experiments demonstrate that MoNE consistently outperforms baseline methods with minimal accuracy degradation across the three dimensions, confirming its effectiveness and robustness. Notably, it improves the average zero shot accuracy across nine downstream tasks by up to 2.71 under 25\% pruning ratio and 3.61 under 50\% pruning. The code is available at https://github.com/zxgx/mode-pd.

[Arxiv](https://arxiv.org/abs/2507.00390)