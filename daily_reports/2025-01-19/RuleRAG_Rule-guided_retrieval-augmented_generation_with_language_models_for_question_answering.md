# RuleRAG: 规则引导的检索增强生成与语言模型在问答中的应用
发布时间：2024年10月15日

`RAG`
> RuleRAG: Rule-guided retrieval-augmented generation with language models for question answering
>
> 检索增强生成（RAG）框架在知识密集型问答（QA）任务中展现了巨大潜力，它通过检索外部语料库并基于增强的上下文生成答案。然而，现有方法仅关注查询本身，既未指定检索器的检索偏好，也未告知生成器如何参考检索到的文档生成答案，这对QA性能构成了挑战。为此，我们提出了基于规则指导的检索增强生成（RuleRAG-ICL），通过引入符号规则作为上下文学习的示范，指导检索器在规则方向上检索逻辑相关的文档，并统一指导生成器根据同一组规则生成答案。此外，查询和规则的组合还可用于监督微调数据，更新检索器和生成器（RuleRAG-FT），以提升基于规则的指令跟随能力，从而检索到更多支持性结果并生成更可接受的答案。为强调规则的归因，我们构建了五个规则感知的QA基准，包括三个时间相关和两个静态场景，并为RuleRAG配备了多种检索器和生成器。实验表明，无需训练的RuleRAG-ICL在五个基准上平均提高了+89.2%的Recall@10检索质量和+103.1%的精确匹配生成准确率，而进一步微调的RuleRAG-FT则持续带来了更显著的性能提升。广泛分析表明，RuleRAG在检索文档数量增加时具有良好的扩展性，并对未训练规则表现出泛化能力。
>
> https://arxiv.org/abs/2410.22353

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.22353](https://arxiv.org/abs/2410.22353)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)