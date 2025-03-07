# # 各层独立调整位置编码，提升长上下文建模性能
发布时间：2025年03月06日


> Layer-Specific Scaling of Positional Encodings for Superior Long-Context Modeling
>
> 尽管大型语言模型（LLMs）在处理长上下文输入方面取得了显著进展，但“中间信息丢失”问题依然存在，即上下文中关键的中间信息常常被低估或丢失。我们通过大量实验发现，这一问题可能源于旋转位置编码（RoPE）中长期衰减的快速下降。为了解决这一问题，我们提出了一种分层特定的位置编码缩放方法，为每一层分配不同的缩放因子，从而减缓RoPE引起的衰减速率，使模型更关注中间上下文。我们还特别设计了一种遗传算法，通过引入贝塞尔曲线来缩小搜索空间，从而高效地为每一层选择最优的缩放因子。通过全面的实验，我们证明了我们的方法显著缓解了“中间信息丢失”问题。在键值检索数据集上，我们的方法平均准确率提升了高达20%。此外，我们还展示了分层插值相较于所有层统一插值的优势：当与位置感应（PI）和动态NTK位置编码方案结合时，它能更好地提升模型的外推能力。
>
> https://arxiv.org/abs/2503.04355

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.04355](https://arxiv.org/abs/2503.04355)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)