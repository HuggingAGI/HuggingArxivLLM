# 基于 LLM 的实用性标注方法：降低检索与 RAG 任务的人工投入
发布时间：2025年04月07日


> Leveraging LLMs for Utility-Focused Annotation: Reducing Manual Effort for Retrieval and RAG
>
> 检索模型通常依赖人工标注的查询-文档相关性标注进行训练和评估，这需要高昂的成本。为了降低成本并充分利用大型语言模型（LLMs）在相关性判断中的潜力，我们希望探索LLM生成的标注能否有效替代人工标注用于训练检索模型。检索通常强调文档与查询的相关性，即“主题相关性”，而在RAG中，文档的价值（或效用）取决于其对答案生成的贡献。认识到这一差异，一些研究者使用LLM在下游任务上的表现作为文档标签，但这种方法需要特定任务的手动答案，导致成本高昂且泛化能力有限。在另一项研究中，通过提示LLM选择有用的文档作为RAG参考，无需人工标注且不特定于任务。如果我们利用LLM的效用判断来标注检索数据，我们可能在大规模语料库中无需人工标注即可保留跨任务的泛化能力。因此，我们研究了在检索和RAG任务上，利用LLM进行效用导向标注的大规模检索训练数据，涵盖领域内和领域外设置。为了减少LLM标注的低质量正样本的影响，我们设计了一种新型损失函数，即Disj-InfoNCE。我们的实验表明：（1）在领域外设置下，基于效用导向标注训练的检索器在两项任务上显著优于基于人工标注训练的检索器，展现了更强大的泛化能力。（2）LLM标注在领域内设置下无法完全替代人工标注。然而，只需加入20%的人工标注数据，基于效用导向标注训练的检索器即可达到完全基于人工标注训练的模型性能。
>
> https://arxiv.org/abs/2504.05220

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.05220](https://arxiv.org/abs/2504.05220)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)