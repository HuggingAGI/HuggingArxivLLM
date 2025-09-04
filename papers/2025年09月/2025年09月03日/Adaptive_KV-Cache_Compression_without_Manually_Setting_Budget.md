# 无需手动设置预算的自适应KV缓存压缩

发布时间：2025年09月03日

`LLM应用` `基础理论`

> Adaptive KV-Cache Compression without Manually Setting Budget

# 摘要

> 大型语言模型（LLMs）推理高度依赖KV缓存加速自回归解码，但其内存占用会随序列长度激增，造成严重的效率瓶颈。现有KV缓存压缩方法陷入“普罗克拉斯提斯之床”困境：它们将多样化任务强行套入固定压缩比，导致资源分配失衡、推理性能受损。为此，我们提出自适应KV缓存压缩方案GVote，无需手动指定预算，却能实现更优的精度-效率平衡。GVote的核心思路是：关键键即未来查询所需键的集合。该方法通过蒙特卡洛风格采样潜在查询，预测未来查询的注意力需求，再聚合选定键，自动确定最优缓存预算。实验结果显示，GVote在GSM8K、RULER和Longbench等多个基准测试中表现优异——相比现有方案，内存占用减少2倍，精度却保持更高或相当水平。

> Large language models (LLMs) inference relies heavily on KV-caches to accelerate autoregressive decoding, but the resulting memory footprint grows rapidly with sequence length, posing significant efficiency challenges. Current KV-cache compression methods suffer from a Procrustes' bed problem: they force diverse workloads into fixed compression ratios, leading to suboptimal resource allocation and inference performance. To this end, we present GVote, an adaptive KV-cache compression scheme that eliminates manual budget specification while achieving superior accuracy-efficiency trade-offs. GVote operates on the principle that the important keys are the aggregation of keys required by future queries. The method predicts future query attention demands by Monte-Carlo style sampling potential queries and aggregating selected keys to determine the optimal cache budget without manual specification. Experimental evaluation demonstrates GVote's effectiveness across multiple benchmarks, including GSM8K, RULER and Longbench. Compared to baselines, GVote exhibits 2$\times$ memory reduction while the accuracy maintains higher or comparable.

[Arxiv](https://arxiv.org/abs/2509.03136)