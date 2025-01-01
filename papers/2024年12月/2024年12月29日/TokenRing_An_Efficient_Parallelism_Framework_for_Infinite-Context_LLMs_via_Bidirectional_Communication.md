# TokenRing：一种通过双向通信为无限上下文的大型语言模型打造的高效并行框架

发布时间：2024年12月29日

`LLM应用` `计算机` `并行计算`

> TokenRing: An Efficient Parallelism Framework for Infinite-Context LLMs via Bidirectional Communication

# 摘要

> 对具有长序列的大型语言模型（LLMs）进行高效并行化至关重要，却颇具挑战，因其计算和内存需求巨大，尤其是源自注意力机制中的通信瓶颈。尽管序列并行（SP）已作为潜在解决方案被引入，但现有方法常因可扩展性受限或效率不高而效果不佳。
    Ring-Attention 虽展现出扩展序列处理的潜力，却因依赖对等（P2P）通信及网络资源利用低效，存在明显局限。随着 SP 程度提升，每步计算时间呈二次方减少，而通信量仅线性减少，致使通信瓶颈加剧。为应对这些难题，我们提出 TokenRing，这一细粒度并行框架借助双向 P2P 通信，有效实现计算与数据传输的重叠。通过划分注意力块，并在全连接网格拓扑中同时传输查询和块输出（即 $block\_out$ 和 $block\_lse$），TokenRing 大幅降低通信开销，优化负载平衡。这些创新提升了分布式 Transformer 模型的可扩展性和效率，对长上下文序列尤为如此。实验结果显示，TokenRing 提高了吞吐量，降低了通信延迟。此外，其设计能无缝适配多种多 GPU 互连方案，如华为 Ascend，确保分布式 LLM 推理和训练具有广泛兼容性和成本效益。代码可在：url{https://github.com/ACA-Lab-SJTU/token-ring}获取。

> Efficient parallelization of Large Language Models (LLMs) with long sequences is essential but challenging due to their significant computational and memory demands, particularly stemming from communication bottlenecks in attention mechanisms. While sequence parallelism (SP) has been introduced as a potential solution, existing methods often suffer from limited scalability or inefficiency, rendering their effectiveness.
  Ring-Attention demonstrates the potential for scaling sequence processing but faces significant limitations due to its reliance on peer-to-peer (P2P) communication and inefficient utilization of network resources. As the degree of SP increases, the quadratic decrease in computation time per step contrasts sharply with the linear reduction in communication volume, exacerbating communication bottlenecks. To address these challenges, we propose TokenRing, a fine-grained parallel framework that leverages bidirectional P2P communication to effectively overlap computation and data transmission. By partitioning the attention block and concurrently transmitting Query and block outputs (i.e., $block\_out$ and $block\_lse$) within a fully connected mesh topology, TokenRing achieves significant reductions in communication overhead and better load balancing. These innovations improve the scalability and efficiency of distributed Transformer models, particularly for long-context sequences. Experimental results demonstrate that TokenRing enhances throughput and reduces communication latency. Moreover, its design adapts seamlessly to various multi-GPU interconnect solutions, such as Huawei Ascend, ensuring broad compatibility and cost-effectiveness for distributed LLM inference and training. The code is available at: url{https://github.com/ACA-Lab-SJTU/token-ring}.

[Arxiv](https://arxiv.org/abs/2412.20501)