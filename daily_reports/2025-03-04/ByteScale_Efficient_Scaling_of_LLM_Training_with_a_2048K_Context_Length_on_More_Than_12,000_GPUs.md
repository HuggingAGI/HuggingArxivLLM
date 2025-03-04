# ByteScale：支持2048K上下文长度，利用超过12000块GPU实现大语言模型训练的高效扩展
发布时间：2025年02月28日


> ByteScale: Efficient Scaling of LLM Training with a 2048K Context Length on More Than 12,000 GPUs
>
> 扩展长上下文能力对大规模语言模型（LLMs）至关重要。为了在长上下文训练中跨多个设备摊销内存消耗，通常使用跨数据划分（即数据并行）和内数据划分（即上下文并行）。当前的训练框架主要将这两种技术视为独立的，并通过建立静态通信组将设备组织成静态网格（例如2D网格）。然而，LLM训练中的序列长度通常会因文本、多模态或强化学习而有所不同。数据异构性与静态网格之间的不匹配导致了冗余通信和计算不平衡，从而降低了训练效率。

在本研究中，我们引入了ByteScale，这是一个高效、灵活且可扩展的LLM训练框架，适用于大规模长序列与短序列混合训练。ByteScale的核心是一种新型并行策略，即混合数据并行（HDP），它通过动态网格设计统一了跨数据和内数据的划分。具体而言，我们构建了一个通信优化器，通过数据感知的分片和动态通信消除短序列的冗余通信，并通过选择性卸载进一步压缩长序列的通信成本。此外，我们还开发了一个平衡调度器，通过并行感知的数据分配来缓解计算不平衡问题。我们在包含超过12,000块GPU的生产集群上，使用从70亿到1410亿参数规模的模型，以及从256K到2048K上下文长度进行了评估。实验结果表明，ByteScale的性能比现有最优训练系统高出7.89倍。
>
> https://arxiv.org/abs/2502.21231

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.21231](https://arxiv.org/abs/2502.21231)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)