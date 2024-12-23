# 逐渐提高警惕与间隔式交流：强化多智能体辩论中的价值对齐

发布时间：2024年12月17日

`Agent` `语言模型` `价值对齐`

> Gradual Vigilance and Interval Communication: Enhancing Value Alignment in Multi-Agent Debates

# 摘要

> 近年来，大型语言模型在满足人类多元需求方面表现卓越。然而，其训练数据可能引入有害内容，凸显出进行强有力价值对齐的必要性。主流方法依赖反馈学习和监督训练，资源耗费大，可能制约模型的全部潜能。多智能体辩论（MAD）通过智能体的交互来生成可靠答案，提供了更高效创新的解决方案。为将 MAD 用于价值对齐，我们探究了辩论结果与个体回应的有益性和无害性的关系，并提出了基于 MAD 的框架——逐步警惕与间隔通信（GVIC）。GVIC 让智能体以不同的警惕程度评估风险，并通过间隔通信交流多样信息。我们从理论上证明 GVIC 在优化辩论效率的同时降低了通信开销。实验结果显示，GVIC 在各种任务和数据集上始终优于基线方法，在降低有害性和防范欺诈方面尤其出色。此外，GVIC 在不同基础模型规模（包括未对齐和已对齐的模型）以及各类任务类型中都展现出强大的适应性。

> In recent years, large language models have shown exceptional performance in fulfilling diverse human needs. However, their training data can introduce harmful content, underscoring the necessity for robust value alignment. Mainstream methods, which depend on feedback learning and supervised training, are resource-intensive and may constrain the full potential of the models. Multi-Agent Debate (MAD) offers a more efficient and innovative solution by enabling the generation of reliable answers through agent interactions. To apply MAD to value alignment, we examine the relationship between the helpfulness and harmlessness of debate outcomes and individual responses, and propose a MAD based framework Gradual Vigilance and Interval Communication (GVIC). GVIC allows agents to assess risks with varying levels of vigilance and to exchange diverse information through interval communication. We theoretically prove that GVIC optimizes debate efficiency while reducing communication overhead. Experimental results demonstrate that GVIC consistently outperforms baseline methods across various tasks and datasets, particularly excelling in harmfulness mitigation and fraud prevention. Additionally, GVIC exhibits strong adaptability across different base model sizes, including both unaligned and aligned models, and across various task types.

[Arxiv](https://arxiv.org/abs/2412.13471)