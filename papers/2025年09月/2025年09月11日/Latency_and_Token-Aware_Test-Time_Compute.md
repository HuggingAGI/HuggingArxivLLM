# 延迟与令牌感知的测试时计算

发布时间：2025年09月11日

`LLM应用` `基础理论`

> Latency and Token-Aware Test-Time Compute

# 摘要

> 推理时扩展技术已然成为提升大型语言模型（LLM）性能的利器，其核心在于生成多个候选响应并从中择优。然而，现有针对测试时计算动态分配的研究往往仅考虑best-of-N等并行生成方法，却忽略了波束搜索这类增量解码方式，且大多忽视了延迟问题，仅聚焦于令牌消耗量。我们将推理时扩展定义为动态计算分配与方法选择问题，即系统需针对每个查询决定采用何种策略以及分配多少计算资源。我们的框架明确整合了令牌成本与实际时钟延迟，后者对用户体验而言至关重要，尤其在智能体工作流中——这类场景下模型需高效处理多个查询。推理基准测试实验显示，我们的方法在性能上始终超越静态策略，在实现理想的准确率-成本平衡的同时，仍具备实际部署价值。

> Inference-time scaling has emerged as a powerful way to improve large language model (LLM) performance by generating multiple candidate responses and selecting among them. However, existing work on dynamic allocation for test-time compute typically considers only parallel generation methods such as best-of-N, overlooking incremental decoding methods like beam search, and has largely ignored latency, focusing only on token usage. We formulate inference-time scaling as a problem of dynamic compute allocation and method selection, where the system must decide which strategy to apply and how much compute to allocate on a per-query basis. Our framework explicitly incorporates both token cost and wall-clock latency, the latter being critical for user experience and particularly for agentic workflows where models must issue multiple queries efficiently. Experiments on reasoning benchmarks show that our approach consistently outperforms static strategies, achieving favorable accuracy-cost trade-offs while remaining practical for deployment.

[Arxiv](https://arxiv.org/abs/2509.09864)