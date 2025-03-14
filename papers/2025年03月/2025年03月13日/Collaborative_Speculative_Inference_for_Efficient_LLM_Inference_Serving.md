# 协作式推测推理：实现高效LLM推理服务的有效方案

发布时间：2025年03月13日

`LLM应用` `系统优化` `分布式计算`

> Collaborative Speculative Inference for Efficient LLM Inference Serving

# 摘要

> 推测推理是一种采用小型推测模型（SSMs）生成草稿标记的创新方法，随后由目标大型语言模型（LLM）进行并行验证。这种方法在减少LLM推理延迟和成本的同时，保持了生成质量，从而显著提升了推理服务的效率。然而，现有推测方法面临资源利用率低和草稿接受度有限等关键挑战，这严重制约了其可扩展性和整体效果。为了解决这些问题，我们提出了CoSine，一种全新的推测推理系统。它通过将顺序推测解码与并行验证解耦，实现了多节点间的高效协作。具体而言，CoSine根据专业领域将推理请求分配到专门的草稿生成器，并引入了基于信心的标记融合机制，综合协同草稿生成器的输出，确保高质量的草稿生成。此外，CoSine采用流水线方式动态编排推测解码和验证的执行，通过批量调度选择性地分组请求，并利用自适应推测控制来最小化空闲时间。通过优化异构节点协作的并行工作流，CoSine实时平衡草稿生成和验证吞吐量，从而最大化资源利用率。实验结果表明，与现有最先进的推测方法相比，CoSine实现了更卓越的性能。尤其值得注意的是，在等效资源成本下，与基线方法相比，CoSine的延迟降低了23.2%，吞吐量提升了32.5%。

> Speculative inference is a promising paradigm employing small speculative models (SSMs) as drafters to generate draft tokens, which are subsequently verified in parallel by the target large language model (LLM). This approach enhances the efficiency of inference serving by reducing LLM inference latency and costs while preserving generation quality. However, existing speculative methods face critical challenges, including inefficient resource utilization and limited draft acceptance, which constrain their scalability and overall effectiveness. To overcome these obstacles, we present CoSine, a novel speculative inference system that decouples sequential speculative decoding from parallel verification, enabling efficient collaboration among multiple nodes. Specifically, CoSine routes inference requests to specialized drafters based on their expertise and incorporates a confidence-based token fusion mechanism to synthesize outputs from cooperating drafters, ensuring high-quality draft generation. Additionally, CoSine dynamically orchestrates the execution of speculative decoding and verification in a pipelined manner, employing batch scheduling to selectively group requests and adaptive speculation control to minimize idle periods. By optimizing parallel workflows through heterogeneous node collaboration, CoSine balances draft generation and verification throughput in real-time, thereby maximizing resource utilization. Experimental results demonstrate that CoSine achieves superior performance compared to state-of-the-art speculative approaches. Notably, with equivalent resource costs, CoSine achieves up to a 23.2% decrease in latency and a 32.5% increase in throughput compared to baseline methods.

[Arxiv](https://arxiv.org/abs/2503.10325)