# exttt{WebANNS}: 浏览器环境下的快速高效近似最近邻搜索

发布时间：2025年07月01日

`RAG` `Web`

> \texttt{WebANNS}: Fast and Efficient Approximate Nearest Neighbor Search in Web Browsers

# 摘要

> 近似最近邻搜索（ANNS）在现代 AI 基础设施中扮演着关键角色，尤其在检索增强生成（RAG）应用中表现突出。为了与基于 LLM 的 Web 应用无缝集成并应对隐私保护及异构设备部署的挑战，众多浏览器端 ANNS 引擎相继问世。然而，浏览器环境带来了独特挑战，包括计算能力受限、外部存储访问问题及内存使用约束，现有顶尖解决方案未能全面解决这些问题。

我们推出了专为浏览器设计的新型 ANNS 引擎——WebANNS。它利用 WebAssembly 克服计算瓶颈，通过懒加载策略优化外部存储数据检索，并采用启发式方法降低内存占用。实验结果显示，WebANNS 在速度和内存效率方面表现卓越，其 99% 分位数查询延迟较现有顶尖引擎提升了高达 743.8 倍，同时内存使用量减少达 39%。特别值得一提的是，WebANNS 将浏览器中的查询时间从 10 秒缩短至 10 毫秒级别，使浏览器端的 ANNS 成为现实，实现了用户可接受的低延迟。


> Approximate nearest neighbor search (ANNS) has become vital to modern AI infrastructure, particularly in retrieval-augmented generation (RAG) applications. Numerous in-browser ANNS engines have emerged to seamlessly integrate with popular LLM-based web applications, while addressing privacy protection and challenges of heterogeneous device deployments. However, web browsers present unique challenges for ANNS, including computational limitations, external storage access issues, and memory utilization constraints, which state-of-the-art (SOTA) solutions fail to address comprehensively.
  We propose \texttt{WebANNS}, a novel ANNS engine specifically designed for web browsers. \texttt{WebANNS} leverages WebAssembly to overcome computational bottlenecks, designs a lazy loading strategy to optimize data retrieval from external storage, and applies a heuristic approach to reduce memory usage. Experiments show that \texttt{WebANNS} is fast and memory efficient, achieving up to $743.8\times$ improvement in 99th percentile query latency over the SOTA engine, while reducing memory usage by up to 39\%. Note that \texttt{WebANNS} decreases query time from 10 seconds to the 10-millisecond range in browsers, making in-browser ANNS practical with user-acceptable latency.

[Arxiv](https://arxiv.org/abs/2507.00521)