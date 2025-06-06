# HALoS: 适用于慢网络的层次化异步本地 SGD 方法，用于地理分布的大规模语言模型训练

发布时间：2025年06月04日

`LLM理论` `人工智能` `分布式计算`

> HALoS: Hierarchical Asynchronous Local SGD over Slow Networks for Geo-Distributed Large Language Model Training

# 摘要

> # 摘要
大型语言模型 (LLMs) 的训练日益依赖地理分布的加速器，由此带来了高昂的跨区域通信成本和硬件资源的不均衡利用。我们提出了一种名为 HALoS 的层次化异步优化框架，通过在每个区域部署本地参数服务器 (LPSs)，并在全局层面设置一个跨区域更新合并的全局参数服务器 (GPS)，有效解决了上述问题。这种层次化设计大幅降低了跨区域通信成本，减少了计算延迟，并充分利用了区域内高速通信链路。我们对 HALoS 在非凸目标下的收敛性进行了深入分析，揭示了层次化动量在异步训练中的理论保障。实验结果表明，HALoS 在地理分布的 LLM 训练中，相较于同步方法快达 7.5 倍，比现有异步方法快达 2.1 倍。尤为关键的是，HALoS 在保持与全同步 SGD 相当的模型质量的同时，大幅缩短了总训练时间。这些成果证实，层次化更新累积和全局模型合并是异构、地理分布环境下高效训练新世代 LLM 的强大工具。


> Training large language models (LLMs) increasingly relies on geographically distributed accelerators, causing prohibitive communication costs across regions and uneven utilization of heterogeneous hardware. We propose HALoS, a hierarchical asynchronous optimization framework that tackles these issues by introducing local parameter servers (LPSs) within each region and a global parameter server (GPS) that merges updates across regions. This hierarchical design minimizes expensive inter-region communication, reduces straggler effects, and leverages fast intra-region links. We provide a rigorous convergence analysis for HALoS under non-convex objectives, including theoretical guarantees on the role of hierarchical momentum in asynchronous training. Empirically, HALoS attains up to 7.5x faster convergence than synchronous baselines in geo-distributed LLM training and improves upon existing asynchronous methods by up to 2.1x. Crucially, HALoS preserves the model quality of fully synchronous SGD-matching or exceeding accuracy on standard language modeling and downstream benchmarks-while substantially lowering total training time. These results demonstrate that hierarchical, server-side update accumulation and global model merging are powerful tools for scalable, efficient training of new-era LLMs in heterogeneous, geo-distributed environments.

[Arxiv](https://arxiv.org/abs/2506.04531)