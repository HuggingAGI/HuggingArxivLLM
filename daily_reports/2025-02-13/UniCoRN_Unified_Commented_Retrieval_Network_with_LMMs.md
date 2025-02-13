# UniCoRN：统一评论检索网络，基于语言模型的融合方法
发布时间：2025年02月12日


> UniCoRN: Unified Commented Retrieval Network with LMMs
>
> 传统多模态检索方法在处理复杂组合查询时存在局限性，难以同时推理查询和检索实体的视觉内容。大语言模型（LMMs）虽能回答更复杂的视觉问题，但缺乏检索相关实体支持答案的能力。为突破这些限制，我们提出了UniCoRN——一种结合了组合式多模态检索与生成式语言方法的统一注释检索网络，超越了传统的检索增强生成（RAG）。通过引入实体适配模块，UniCoRN能够将检索到的多模态实体重新注入LMM，使其在生成答案和注释时能够关注这些实体。保持基础LMM冻结的同时，UniCoRN不仅保留了原有能力，还实现了检索与文本生成的无缝结合。为验证这些新能力，我们提出了带评论的检索任务（CoR）及其对应数据集，旨在准确回答问题的同时生成详细注释。实验结果显示，与最先进方法相比，UniCoRN在组合式多模态检索中召回率提升了+4.5%，在CoR任务中评论的METEOR和BEM指标分别提升了+14.9%和+18.4%。
>
> https://arxiv.org/abs/2502.08254

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.08254](https://arxiv.org/abs/2502.08254)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)