# KeyDiff: 基于键相似度的 KV 缓存替换策略，优化资源受限环境中的长上下文 LLM 推理性能

发布时间：2025年05月20日

`LLM应用` `人工智能` `计算机科学`

> KeyDiff: Key Similarity-Based KV Cache Eviction for Long-Context LLM Inference in Resource-Constrained Environments

# 摘要

> 我们在研究中发现，大型语言模型（LLM）推理过程中，几何上独特的键通常与高注意力分数相关联。基于这一现象，我们提出了一种名为KeyDiff的无训练KV缓存替换方法，该方法仅依赖于键的相似性。与其它KV缓存替换方法不同，KeyDiff能够在严格的资源限制下处理任意长度的输入提示，并高效生成响应。我们通过理论分析，揭示了键的多样性和注意力分数之间的关系，为KeyDiff提供了坚实的理论基础。实验结果表明，KeyDiff能够高效识别需要保留的最重要token。值得注意的是，KeyDiff不依赖于注意力分数，因此可以与优化的注意力机制（如FlashAttention）兼容。在严格的内存预算下，我们在Llama和Qwen模型家族上验证了KeyDiff的有效性：在LongBench基准测试中，KeyDiff在8K缓存预算（相比非替换基线，缓存大小减少约23%）下，Llama 3.1-8B和Llama 3.2-3B的性能差距小于0.04%。在Math500推理基准测试中，Deepseek-R1-Distill-Llama-8B也达到了接近基线的性能，与其它token替换方法相比，端到端推理延迟降低了高达30%。

> We demonstrate that geometrically distinctive keys during LLM inference tend to have high attention scores. Based on the phenomenon we propose KeyDiff, a training-free KV cache eviction method based solely on key similarity. Unlike other KV cache eviction methods, KeyDiff can process arbitrarily long prompts within strict resource constraints and efficiently generate responses. We provide a theoretical basis for KeyDiff by relating key diversity with attention scores. These results imply KeyDiff can efficiently identify the most important tokens to retain. Notably KeyDiff does not rely on attention scores, allowing the use of optimized attention mechanisms like FlashAttention. Under a strict memory allowance, we demonstrate the effectiveness of KeyDiff for the Llama and Qwen model families by observing a performance gap of less than 0.04% with 8K cache budget ($\sim$23% KV cache reduction) from the non-evicting baseline on LongBench for Llama 3.1-8B and Llama 3.2-3B. We also observe near baseline performance for Deepseek-R1-Distill-Llama-8B on the Math500 reasoning benchmark and decrease end-to-end inference latency by up to 30% compared to the other token-eviction methods.

[Arxiv](https://arxiv.org/abs/2504.15364)