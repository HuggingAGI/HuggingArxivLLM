# TransMLA：多头潜在注意力机制，一切你所需
发布时间：2025年02月13日


> TransMLA: Multi-Head Latent Attention Is All You Need
>
> 现代大型语言模型（LLMs）在当前硬件上常面临通信瓶颈，而非单纯计算限制。多头潜在注意力（MLA）通过在键值（KV）层使用低秩矩阵，允许压缩后的潜在KV状态缓存，从而显著减少KV缓存大小，提升推理速度。此外，MLA借助上投影矩阵增强表达能力，以额外计算换取更低通信开销。尽管MLA在Deepseek V2/V3/R1中已展现高效与有效，但多数模型提供商仍依赖组查询注意力（GQA），尚未计划采用MLA。本文证明GQA可始终用MLA表示，保持相同KV缓存开销，反之则不然。为推广MLA应用，我们推出TransMLA——一种后训练方法，可将基于GQA的主流预训练模型（如LLaMA、Qwen、Mixtral）转换为MLA模型。转换后，模型可通过额外训练提升表达能力，而不增加KV缓存大小。此外，我们计划开发MLA专用推理加速技术，保持转换模型的低延迟，从而实现更高效的Deepseek R1蒸馏。
>
> https://arxiv.org/abs/2502.07864

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.07864](https://arxiv.org/abs/2502.07864)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)