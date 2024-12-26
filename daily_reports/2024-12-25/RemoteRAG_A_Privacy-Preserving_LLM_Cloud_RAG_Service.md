# RemoteRAG：一项具备隐私保护功能的 LLM 云 RAG 服务
发布时间：2024年12月17日

`RAG`
> RemoteRAG: A Privacy-Preserving LLM Cloud RAG Service
>
> 检索增强生成（RAG）能从可靠文献中检索相关文档，并融入用户查询的语境，从而提升大型语言模型的服务质量。近来，云 RAG 服务兴起，方便了用户查询相关文档。但直接向云端发送查询，可能导致隐私泄露。本文中，我们率先正式定义了保护隐私的云 RAG 服务来守护用户查询，并提出 RemoteRAG 作为兼顾隐私、效率与准确性的解决方案。在隐私方面，我们引入$(n,ε)$-DistanceDP 来刻画用户查询的隐私泄露以及从相关文档推断出的泄露情况。在效率方面，我们把搜索范围从全部文档缩小到与由$(n,ε)$-DistanceDP 生成的扰动嵌入相关的少量选定文档，大幅降低了隐私保护所需的计算和通信成本。在准确性方面，我们通过详尽的理论分析，确保小范围涵盖与用户查询相关的目标文档。实验结果显示，RemoteRAG 能够抵御现有的嵌入反转攻击方法，且在各种设置下检索时毫无损失。此外，RemoteRAG 效率颇高，从总计 10^6 个文档中检索时，仅需 0.67 秒和 46.66KB 的数据传输（未优化的隐私保护方案则需 2.72 小时和 1.43GB）。
>
> https://arxiv.org/abs/2412.12775

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.12775](https://arxiv.org/abs/2412.12775)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)