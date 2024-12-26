# KunServe：具备以参数为中心的内存管理，实现弹性且高效的大型语言模型服务

发布时间：2024年12月24日

`LLM应用` `云计算` `人工智能`

> KunServe: Elastic and Efficient Large Language Model Serving with Parameter-centric Memory Management

# 摘要

> 大型语言模型（LLM）服务具有有状态的特性，在负载突发或诸如思维链推理这类长生成请求的情况下，极易使珍贵的 GPU 内存吃紧，从而因传入请求排队导致延迟峰值。然而，当下前沿的以 KVCache 为核心的方法通过丢弃、迁移或交换 KVCache 来应对负载峰值，但这在正在处理的请求和新传入请求的性能之间存在关键权衡，所以仍严重违反 SLO。本文有个重要发现，即模型参数与请求无关且在 GPU 间复制，于是提出一种以参数为核心的方法，通过有选择地丢弃复制的参数为请求预留宝贵内存。但 LLM 要求 KVCache 与模型参数绑定保存，所以丢弃参数可能造成巨大的计算浪费或漫长的网络延迟，影响所有正在进行的请求。基于注意力运算符可与其他运算符解耦这一观察，本文进一步通过流水线并行提出一种新颖的远程注意力机制，以便利用从远程 GPU 上的参数借来的额外内存服务即将到来的请求。本文还处理了其他若干挑战，包括与不完整参数灵活交换 KVCache、生成平衡内存需求与协作执行开销的恰当方案，以及在节流结束时无缝恢复参数。评估显示，与最先进的技术相比，KUNSERVE 使节流情况下请求的尾部 TTFT 最多降低了 27.3 倍。

> The stateful nature of large language model (LLM) servingcan easily throttle precious GPU memory under load burstor long-generation requests like chain-of-thought reasoning,causing latency spikes due to queuing incoming requests. However, state-of-the-art KVCache centric approaches handleload spikes by dropping, migrating, or swapping KVCache,which faces an essential tradeoff between the performance ofongoing vs. incoming requests and thus still severely violatesSLO.This paper makes a key observation such that model param-eters are independent of the requests and are replicated acrossGPUs, and thus proposes a parameter-centric approach byselectively dropping replicated parameters to leave preciousmemory for requests. However, LLM requires KVCache tobe saved in bound with model parameters and thus droppingparameters can cause either huge computation waste or longnetwork delay, affecting all ongoing requests. Based on the ob-servation that attention operators can be decoupled from otheroperators, this paper further proposes a novel remote attentionmechanism through pipeline parallelism so as to serve up-coming requests with the additional memory borrowed fromparameters on remote GPUs. This paper further addresses sev-eral other challenges including lively exchanging KVCachewith incomplete parameters, generating an appropriate planthat balances memory requirements with cooperative exe-cution overhead, and seamlessly restoring parameters whenthe throttling has gone. Evaluations show thatKUNSERVEreduces the tail TTFT of requests under throttling by up to 27.3x compared to the state-of-the-art.

[Arxiv](https://arxiv.org/abs/2412.18169)