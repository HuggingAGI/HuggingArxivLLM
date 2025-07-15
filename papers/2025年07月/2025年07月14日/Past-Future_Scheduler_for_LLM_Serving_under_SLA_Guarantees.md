# 基于 SLA 保障的 LLM 服务过去-未来调度器

发布时间：2025年07月14日

`LLM应用

理由：这篇论文主要探讨了如何优化大语言模型（LLMs）在实际服务框架中的部署和性能，特别是通过设计一种新型的Past-Future调度器来提高吞吐量。它关注的是如何在实际应用中更高效地利用资源，属于LLM应用领域的研究。` `服务框架`

> Past-Future Scheduler for LLM Serving under SLA Guarantees

# 摘要

> 大语言模型（LLMs）的应用正蓬勃发展。为了降低部署成本，持续批量处理已成为当前服务框架中的必备功能。然而，由于请求输出长度的多样性，现有框架往往采用激进或保守的调度器，导致内存消耗的显著高估或低估，进而引发有害请求逐出或长时间排队的问题，在严格的SLA保障下难以实现令人满意的吞吐量。为解决这一问题，我们提出了一种新型Past-Future调度器，通过分析请求输出长度的历史分布，并计算每个未来时间点的内存占用，精确估计运行批次所需的峰值内存资源。它适用于所有类型输入输出长度分布的应用，平衡了请求排队与有害逐出之间的权衡，从而持续实现更好的吞吐量。为了验证所提出的调度器的有效性，我们开发了一个高性能的LLM服务框架LightLLM，该框架实现了Past-Future调度器。与现有的激进或保守调度器相比，LightLLM在高负载下实现了比其他调度器高出2-3倍的吞吐量。LightLLM是开源的，以推动这一方向的研究（https://github.com/ModelTC/lightllm）。

> The exploration and application of Large Language Models (LLMs) is thriving. To reduce deployment costs, continuous batching has become an essential feature in current service frameworks. The effectiveness of continuous batching relies on an accurate estimate of the memory requirements of requests. However, due to the diversity in request output lengths, existing frameworks tend to adopt aggressive or conservative schedulers, which often result in significant overestimation or underestimation of memory consumption. Consequently, they suffer from harmful request evictions or prolonged queuing times, failing to achieve satisfactory throughput under strict Service Level Agreement (SLA) guarantees (a.k.a. goodput), across various LLM application scenarios with differing input-output length distributions. To address this issue, we propose a novel Past-Future scheduler that precisely estimates the peak memory resources required by the running batch via considering the historical distribution of request output lengths and calculating memory occupancy at each future time point. It adapts to applications with all types of input-output length distributions, balancing the trade-off between request queuing and harmful evictions, thereby consistently achieving better goodput. Furthermore, to validate the effectiveness of the proposed scheduler, we developed a high-performance LLM serving framework, LightLLM, that implements the Past-Future scheduler. Compared to existing aggressive or conservative schedulers, LightLLM demonstrates superior goodput, achieving up to 2-3$\times$ higher goodput than other schedulers under heavy loads. LightLLM is open source to boost the research in such direction (https://github.com/ModelTC/lightllm).

[Arxiv](https://arxiv.org/abs/2507.10150)