# ## O1 Embedder：让检索器先思考再行动
发布时间：2025年02月11日


> O1 Embedder: Let Retrievers Think Before Action
>
> 受此启发，我们致力于为检索模型开发类似的能力，以应对领域内的关键挑战，包括多任务检索、零样本检索以及需要复杂关系推理的任务。为此，我们提出了一种名为 O1 Embedder 的创新方法，该方法在检索目标文档之前，先为输入查询生成有用的思考。为实现这一目标，我们克服了两大技术难题。首先，我们设计了一个数据合成流程，通过从 LLM 专家生成初始思考，并利用检索委员会进行优化，从而为 O1 Embedder 创建训练信号。其次，我们优化了训练过程，使预训练模型能够通过行为克隆生成检索思考，并通过对比学习实现密集检索。通过全面的实验评估，我们在涵盖领域内和领域外场景的 12 个流行数据集上取得了显著改进。这些结果凸显了 O1 Embedder 的卓越准确性和泛化能力，为下一代信息检索基础模型的开发铺平了道路。
>
> https://arxiv.org/abs/2502.07555

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.07555](https://arxiv.org/abs/2502.07555)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)