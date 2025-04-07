# EnrichIndex: 利用LLMs离线增强检索索引
发布时间：2025年04月04日

`RAG`
> EnrichIndex: Using LLMs to Enrich Retrieval Indices Offline
>
> 现有信息检索系统在目标文档语言与用户查询语言高度匹配时表现出色。但在实际应用中，系统通常需要隐式判断文档的相关性。例如，技术文本或表格可能通过特定术语或结构隐含与用户查询的相关性，而非在内容中明确表达。大型语言模型（LLMs）在识别这种隐含相关性方面具有巨大潜力，得益于其强大的推理能力。然而，当前基于LLM的增强检索受限于高延迟和计算成本，因为LLM通常需要在线为每个新查询计算查询-文档相关性。为解决这一问题，我们引入了EnrichIndex方法。该方法在文档摄取阶段对检索语料库中的所有文档进行一次遍历，利用LLM离线构建语义增强的检索索引。此外，语义增强的索引可以与现有在线检索方法互补，提升LLM重排序器的性能。我们在涉及段落和表格的五个检索任务上评估了EnrichIndex，发现它优于强大的在线LLM基线系统。与强基线相比，其在召回率@10和NDCG@10指标上分别提升了11.7和10.6个点。在在线调用LLM方面，它处理的token数量减少了293.3倍，大幅降低了在线延迟和成本。总体而言，EnrichIndex是一种有效的方法，通过利用LLM强大的推理能力，离线构建更好的检索索引。
>
> https://arxiv.org/abs/2504.03598

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.03598](https://arxiv.org/abs/2504.03598)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)