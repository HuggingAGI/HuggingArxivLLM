# Summarize-Exemplify-Reflect：数据驱动的洞察提炼助力LLMs实现少样本表格分类

发布时间：2025年08月29日

`LLM应用` `基础理论`

> Summarize-Exemplify-Reflect: Data-driven Insight Distillation Empowers LLMs for Few-shot Tabular Classification

# 摘要

> 近期研究表明，大型语言模型（LLMs）在少样本表格分类任务中展现出潜力，但也指出结构化数据的多样性带来了不小挑战。为此，我们提出将数据提炼为可落地的洞察，助力LLMs实现稳健高效的分类。借鉴人类学习的过程，我们提出了InsightTab——一个遵循分而治之、先易后难及反思学习原则的洞察提炼框架。该方法通过LLMs与数据建模技术的深度协作，整合了规则总结、策略性示例选取及洞察反思环节。这些洞察帮助LLMs将其通用知识与能力更好地适配特定表格任务的具体需求。我们在九个数据集上对InsightTab展开了全面评估，结果显示，相比现有最优方法，InsightTab的性能得到了稳定提升。消融实验进一步验证了原则指导下的提炼过程，分析也证实了InsightTab在利用标记数据和缓解偏差方面的出色表现。

> Recent studies show the promise of large language models (LLMs) for few-shot tabular classification but highlight challenges due to the variability in structured data. To address this, we propose distilling data into actionable insights to enable robust and effective classification by LLMs. Drawing inspiration from human learning processes, we introduce InsightTab, an insight distillation framework guided by principles of divide-and-conquer, easy-first, and reflective learning. Our approach integrates rule summarization, strategic exemplification, and insight reflection through deep collaboration between LLMs and data modeling techniques. The obtained insights enable LLMs to better align their general knowledge and capabilities with the particular requirements of specific tabular tasks. We extensively evaluate InsightTab on nine datasets. The results demonstrate consistent improvement over state-of-the-art methods. Ablation studies further validate the principle-guided distillation process, while analyses emphasize InsightTab's effectiveness in leveraging labeled data and managing bias.

[Arxiv](https://arxiv.org/abs/2508.21561)