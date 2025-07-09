# FlowSpec: 持续流水线推测解码实现高效分布式LLM推理

发布时间：2025年07月03日

`LLM应用` `边缘计算` `分布式计算`

> FlowSpec: Continuous Pipelined Speculative Decoding for Efficient Distributed LLM Inference

# 摘要

> 分布式推理为在边缘网络中实现大型语言模型（LLMs）推理提供了一种有前途的方法。它通过将推理过程分配到多个设备上，确保LLMs能够适应设备内存。近年来，基于流水线的方法展示了实现通信与计算并行化的潜力，从而有助于降低推理延迟。然而，当网络边缘的推理请求稀疏时，这种方法的优势会显著减弱，因为流水线通常处于低利用率状态。针对这一问题，我们提出了	extbf{FlowSpec}，一种基于流水线并行树的推测性解码框架，旨在实现高效的边缘分布式LLM推理。FlowSpec通过三种关键机制优化解码效率：1) 基于得分的分步验证优先处理更重要的草稿令牌，以使更早被接受的令牌优先；2) 高效的草稿管理在验证过程中剪除无效令牌，同时保持正确的因果关系；3) 动态草稿扩展策略以提供高质量的推测输入。这些技术协同工作，显著提升了流水线利用率和推测效率。我们在实际测试床上对FlowSpec进行了全面评估，并与其他基线方法进行了对比。实验结果表明，与基线相比，FlowSpec在各种模型和配置下显著提高了推理速度，实现了1.36×-1.77×的速度提升。我们的代码已在\href{https://github.com/Leosang-lx/FlowSpec#}{https://github.com/Leosang-lx/FlowSpec\#}公开发布，方便研究和实践使用。

> Distributed inference serves as a promising approach to enabling the inference of large language models (LLMs) at the network edge. It distributes the inference process to multiple devices to ensure that the LLMs can fit into the device memory. Recent pipeline-based approaches have the potential to parallelize communication and computation, which helps reduce inference latency. However, the benefit diminishes when the inference request at the network edge is sparse, where pipeline is typically at low utilization. To enable efficient distributed LLM inference at the edge, we propose \textbf{FlowSpec}, a pipeline-parallel tree-based speculative decoding framework. FlowSpec incorporates three key mechanisms to improve decoding efficiency: 1) score-based step-wise verification prioritizes more important draft tokens to bring earlier accpeted tokens; 2) efficient draft management to prune invalid tokens while maintaining correct causal relationship during verification; 3) dynamic draft expansion strategies to supply high-quality speculative inputs. These techniques work in concert to enhance both pipeline utilization and speculative efficiency. We evaluate FlowSpec on a real-world testbed with other baselines. Experimental results demonstrate that our proposed framework significantly improves inference speed across diverse models and configurations, achieving speedup ratios 1.36$\times$-1.77$\times$ compared to baselines. Our code is publicly available at \href{https://github.com/Leosang-lx/FlowSpec#}{https://github.com/Leosang-lx/FlowSpec\#}

[Arxiv](https://arxiv.org/abs/2507.02620)