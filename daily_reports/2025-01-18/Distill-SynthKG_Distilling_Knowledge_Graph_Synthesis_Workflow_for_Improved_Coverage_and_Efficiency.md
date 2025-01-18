# Distill-SynthKG: 优化知识图谱合成流程，提升覆盖范围与效率
发布时间：2024年10月21日

`RAG`
> Distill-SynthKG: Distilling Knowledge Graph Synthesis Workflow for Improved Coverage and Efficiency
>
> # 摘要
大型语言模型（LLMs）生成的知识图谱（KGs）在需要知识密集型推理的检索增强生成（RAG）应用中日益重要。然而，现有的KG提取方法主要依赖基于提示的方法，处理大规模语料库时效率低下，且在处理长文档时容易丢失信息。此外，无本体KG构建的评估数据集和方法尚不完善。为此，我们提出了SynthKG，一种基于LLMs的多步骤、文档级无本体KG合成工作流。通过微调较小的LLM，我们将多步骤过程简化为单步骤KG生成方法Distill-SynthKG，显著减少了LLM推理调用次数。我们还重新利用现有问答数据集构建KG评估数据集，并引入新的评估指标。基于Distill-SynthKG生成的KGs，我们设计了一个新颖的图检索框架用于RAG。实验表明，Distill-SynthKG不仅在KG质量上超越所有基线模型（包括高达八倍大的模型），还在检索和问答任务中表现优异。我们的图检索框架在多个基准数据集上也优于所有KG检索方法。我们公开发布了SynthKG数据集和Distill-SynthKG模型，以促进进一步研究。
>
> https://arxiv.org/abs/2410.16597

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.16597](https://arxiv.org/abs/2410.16597)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)