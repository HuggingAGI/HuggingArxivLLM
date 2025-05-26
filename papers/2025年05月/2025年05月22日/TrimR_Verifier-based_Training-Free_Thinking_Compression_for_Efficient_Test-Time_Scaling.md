# TrimR：基于验证机制的无训练思维压缩，实现高效测试时扩展

发布时间：2025年05月22日

`LLM应用` `人工智能`

> TrimR: Verifier-based Training-Free Thinking Compression for Efficient Test-Time Scaling

# 摘要

> 大型推理模型（LRMs）通过扩展的思维链（CoT）推理，在处理复杂任务方面表现卓越。然而，测试时的扩展方法虽能提升准确性，却带来了显著的解码开销。研究发现，LRMs常生成冗余的思考链，表现出过度与不足的结构化思考模式。为此，我们提出TrimR——一个无需训练、高效且基于验证器的动态CoT压缩框架，专为生产级部署优化。该方法采用轻量级验证器检测并截断冗余思考，无需微调。我们不仅展示了核心算法，还展示了针对高吞吐量工业应用设计的异步在线系统。实验结果表明，在大批次工作负载下，TrimR显著提升了推理效率，推理时间提升高达70%，同时几乎不影响准确性。

> Large Reasoning Models (LRMs) demonstrate exceptional capability in tackling complex mathematical, logical, and coding tasks by leveraging extended Chain-of-Thought (CoT) reasoning. Test-time scaling methods, such as prolonging CoT with explicit token-level exploration, can push LRMs' accuracy boundaries, but they incur significant decoding overhead. A key inefficiency source is LRMs often generate redundant thinking CoTs, which demonstrate clear structured overthinking and underthinking patterns. Inspired by human cognitive reasoning processes and numerical optimization theories, we propose TrimR, a verifier-based, training-free, efficient framework for dynamic CoT compression to trim reasoning and enhance test-time scaling, explicitly tailored for production-level deployment. Our method employs a lightweight, pretrained, instruction-tuned verifier to detect and truncate redundant intermediate thoughts of LRMs without any LRM or verifier fine-tuning. We present both the core algorithm and asynchronous online system engineered for high-throughput industrial applications. Empirical evaluations on Ascend NPUs and vLLM show that our framework delivers substantial gains in inference efficiency under large-batch workloads. In particular, on the four MATH500, AIME24, AIME25, and GPQA benchmarks, the reasoning runtime of Pangu-R-38B, QwQ-32B, and DeepSeek-R1-Distill-Qwen-32B is improved by up to 70% with negligible impact on accuracy.

[Arxiv](https://arxiv.org/abs/2505.17155)