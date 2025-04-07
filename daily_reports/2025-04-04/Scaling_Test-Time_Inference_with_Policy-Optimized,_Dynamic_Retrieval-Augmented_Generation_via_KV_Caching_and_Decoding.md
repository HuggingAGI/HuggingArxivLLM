# # 研究标题  
基于策略优化的动态检索增强生成，通过 KV 缓存与解码扩展测试时推理能力
发布时间：2025年04月02日

`RAG`
> Scaling Test-Time Inference with Policy-Optimized, Dynamic Retrieval-Augmented Generation via KV Caching and Decoding
>
> 我们提出了一套全新的框架，通过动态检索策略与强化微调技术，全面升级检索增强生成（RAG）系统。该方案显著提升了大型语言模型在知识密集型任务中的表现，涵盖开放领域问答与复杂推理等场景。框架巧妙融合两大核心技术：基于策略优化的增强生成（PORAG），专注于优化检索信息的运用；以及自适应令牌层注意力评分（ATLAS），可根据上下文需求动态调整检索时机与内容。两者相辅相成，不仅提升了检索内容的利用率，更确保了其相关性，从而显著改善了事实准确性与响应质量。

这套框架作为轻量级解决方案，与任何基于Transformer的大型语言模型无缝兼容，无需额外训练即可投入使用。在知识密集型任务中，它展现了卓越的性能，显著提升了RAG场景下的输出准确性。我们还创新性地提出了CRITIC方法，通过令牌重要性评估实现键值缓存的选择性压缩，有效缓解了长上下文应用中的内存瓶颈。框架内置的推理时缩放技术，能够动态平衡推理深度与计算资源，配合优化的解码策略，进一步提升了推理速度。

实验结果表明，与传统RAG系统相比，我们的框架在基准数据集上实现了三大突破：显著减少了幻觉现象，大幅增强了领域特定推理能力，同时在效率与可扩展性方面取得了显著提升。这一集成方案为打造更稳健、更高效、更具扩展性的RAG系统开辟了全新道路，为多领域应用注入了强大动力。
>
> https://arxiv.org/abs/2504.01281

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.01281](https://arxiv.org/abs/2504.01281)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)