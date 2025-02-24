# Oreo：一款增强检索增强生成的插件式上下文重构器
发布时间：2025年02月20日


> Oreo: A Plug-in Context Reconstructor to Enhance Retrieval-Augmented Generation
>
> 大型语言模型（LLMs）在NLP任务中表现卓越，但受限于其参数化知识和领域专业性的不足，仍易出现幻觉。为解决这一问题，检索增强生成（RAG）通过整合外部文档检索来扩充LLMs的知识库。具体而言，RAG根据查询从外部语料库中检索文档片段，并将其作为下游语言模型生成答案的上下文。然而，检索到的知识来源常包含不相关或错误信息，影响了RAG在下游任务中的效果。为克服这一限制，我们提出了一种紧凑、高效且可插拔的模块，用于优化外部知识源。该模块通过提取最相关和支持的信息并进行重构，将其组织成简洁且与查询相关的格式。通过监督微调、对比多任务学习以及基于强化学习的对齐这三阶段训练范式，该模块优先考虑关键知识并使其与生成器的偏好保持一致。这种方法使LLMs能够生成更准确、可靠且语境恰当的输出。
>
> https://arxiv.org/abs/2502.13019

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.13019](https://arxiv.org/abs/2502.13019)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)