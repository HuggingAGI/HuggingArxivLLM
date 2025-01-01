# 借助视觉大语言模型提升表格识别：一个基准及邻域引导的工具链推理器
发布时间：2024年12月29日

`图表问答`
> Enhancing Table Recognition with Vision LLMs: A Benchmark and Neighbor-Guided Toolchain Reasoner
>
> 预训练的基础模型近来在结构化表格的理解与推理方面进展显著。然而，即便在表格语义理解、表格问答等领域有所突破，利用视觉大型语言模型（VLLMs）识别非结构化表格的结构和内容，仍有待深入探索。在本研究中，我们借助在无训练推理范式中运用 VLLMs 来填补这一研究空白。首先，我们设计了一个涵盖与表格识别相关的各种层次维度的基准。接着，通过使用预训练的 VLLMs 进行深入评估，发现低质量图像输入是识别过程中的关键瓶颈。受此启发，我们提出了邻居引导的工具链推理器（NGTR）框架，其特色在于整合了多个用于低级视觉处理操作的轻量级模型，以解决低质量输入图像的问题。具体来说，我们利用邻居检索机制来引导生成多个工具调用计划，将相似邻居的工具选择经验迁移到给定输入，从而利于选择合适的工具。此外，我们引入了一个反思模块来监督工具调用过程。在公共表格识别数据集上的大量实验表明，我们的方法显著提升了原始 VLLMs 的识别能力。我们认为，所设计的基准和提出的 NGTR 框架能够为表格识别提供一种别样的解决方案。
>
> https://arxiv.org/abs/2412.20662

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.20662](https://arxiv.org/abs/2412.20662)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)