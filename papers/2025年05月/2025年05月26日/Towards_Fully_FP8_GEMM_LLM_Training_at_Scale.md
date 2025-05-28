# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月26日

`LLM理论` `机器学习`

> Towards Fully FP8 GEMM LLM Training at Scale

# 摘要

> FP8数据格式在LLM预训练中潜力巨大，但因其在大规模场景下稳定性不足，应用受限。现有方法多依赖次优的精细FP8内核，或在敏感组件（如注意力投影）中退回到更高精度的矩阵乘法（GEMMs），这导致吞吐量增益受限。我们提出了一种全新的LLM架构，首次在变压器块的前向和后向传递中全面支持GEMMs的FP8计算。这一突破不仅在大规模场景下实现了前所未有的吞吐量提升，更达到了与标准BF16训练相当的下游性能。通过减少大型异常激活，我们的架构设计为长期稳定的FP8训练奠定了基础。此外，我们还明确了关键指标，用于实时监控低精度训练状态并预测潜在的性能发散风险。

> Despite the significant potential of FP8 data formats for large language model (LLM) pre-training, their adoption has been limited due to challenges in maintaining stability at scale. Existing approaches often rely on suboptimal fine-grained FP8 kernels or fall back to higher-precision matrix multiplications (GEMMs) in sensitive components, such as attention projections, compromising potential throughput gains. We introduce a new class of LLM architectures that, for the first time, support FP8 computation for all GEMMs within transformer blocks during both forward and backward passes. This enables unprecedented throughput gains, particularly at scale, while matching the downstream performance of standard BF16 training. Our architecture design reduces large outlier activations, promoting stable long-term FP8 training. In addition, we identify key metrics to monitor low-precision training and predict potential future divergences.

[Arxiv](https://arxiv.org/abs/2505.20524)