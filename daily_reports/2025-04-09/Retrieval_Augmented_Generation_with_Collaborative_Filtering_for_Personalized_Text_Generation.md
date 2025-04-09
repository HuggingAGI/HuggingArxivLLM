# 通过协同推荐增强检索，实现个性化文本生成
发布时间：2025年04月08日

`RAG`
> Retrieval Augmented Generation with Collaborative Filtering for Personalized Text Generation
>
> 大规模语言模型的个性化生成领域近期备受关注，旨在让模型产出符合用户偏好的内容。个性化检索增强生成（Personalized RAG）是一种常用方法，通过检索用户历史记录中的相关文档，反映其偏好并提升生成效果。然而，现有方法忽视了相似用户的历史记录对当前用户个性化生成的辅助作用，即用户间的协同信息同样能带来提升。受推荐系统中协同过滤技术的启发，我们提出了一种名为 CFRAG 的方法，将协同过滤引入 RAG，以实现更高效的个性化文本生成。这一创新面临两大挑战：(1) 如何在缺乏显式用户相似性标签的情况下整合协同信息？(2) 如何精准检索支持个性化生成的文档？针对第一个挑战，我们采用对比学习训练用户嵌入，从而检索相似用户并引入协同信息。针对第二个挑战，我们设计了一种个性化检索器和重排序器，从这些用户的过往记录中筛选出最相关的 top-$k$ 文档。在检索和重排序过程中，我们充分考虑了用户的偏好。随后，我们利用 LLM 的反馈对检索器和重排序器进行微调，使其能够精准捕捉个性化生成需求。实验结果表明，CFRAG 在语言模型个性化（LaMP）基准测试中表现优异。进一步分析证实了协同信息整合的重要性。
>
> https://arxiv.org/abs/2504.05731

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.05731](https://arxiv.org/abs/2504.05731)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)