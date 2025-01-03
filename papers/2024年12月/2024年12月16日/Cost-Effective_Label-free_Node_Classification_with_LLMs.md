# 基于LLMs的高性价比无标签节点分类

发布时间：2024年12月16日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）与图神经网络（GNNs）结合，以解决图数据节点分类中的标注数据不足问题。论文提出的Cella框架利用LLMs的零-shot能力和海量知识来生成伪标签，并通过GNNs进行迭代优化。这种方法属于LLM在实际应用中的创新使用，因此应归类为LLM应用。` `图数据` `节点分类`

> Cost-Effective Label-free Node Classification with LLMs

# 摘要

> # 摘要
图神经网络（GNNs）凭借其强大的图结构与属性融合能力，已成为图数据节点分类的首选模型。然而，这些模型高度依赖高质量标注数据，而实际中获取这些数据成本高昂。随着大型语言模型（LLMs）的崛起，利用其卓越的零-shot能力和海量知识进行节点标注成为了一种新思路。尽管已有一些成果，但这种方法要么需要大量查询LLMs，要么因LLMs生成的噪声标签而影响性能。
为此，本文提出了Cella，一种将LLMs高效集成到GNNs中的主动自训练框架。Cella的核心设计是通过GNNs迭代筛选少量“关键”样本，并利用LLMs和GNNs作为额外监督信号，为这些样本生成信息丰富的伪标签，从而提升模型训练效果。Cella包含三大模块：（i）一种高效的主动节点选择策略，用于初始标注；（ii）基于标签不和谐性和熵的“关键”节点筛选机制；（iii）结合LLMs和GNNs并优化拓扑的标签精炼模块。我们在五个文本属性图数据集上的实验表明，在相同LLMs查询预算下，Cella在无标签节点分类任务中显著优于现有技术。特别是在包含14.3k个节点的DBLP数据集上，Cella以不到一分钱的成本实现了8.08%的准确率提升。

> Graph neural networks (GNNs) have emerged as go-to models for node classification in graph data due to their powerful abilities in fusing graph structures and attributes. However, such models strongly rely on adequate high-quality labeled data for training, which are expensive to acquire in practice. With the advent of large language models (LLMs), a promising way is to leverage their superb zero-shot capabilities and massive knowledge for node labeling. Despite promising results reported, this methodology either demands considerable queries to LLMs, or suffers from compromised performance caused by noisy labels produced by LLMs.
  To remedy these issues, this work presents Cella, an active self-training framework that integrates LLMs into GNNs in a cost-effective manner. The design recipe of Cella is to iteratively identify small sets of "critical" samples using GNNs and extract informative pseudo-labels for them with both LLMs and GNNs as additional supervision signals to enhance model training. Particularly, Cella includes three major components: (i) an effective active node selection strategy for initial annotations; (ii) a judicious sample selection scheme to sift out the "critical" nodes based on label disharmonicity and entropy; and (iii) a label refinement module combining LLMs and GNNs with rewired topology. Our extensive experiments over five benchmark text-attributed graph datasets demonstrate that Cella significantly outperforms the state of the arts under the same query budget to LLMs in terms of label-free node classification. In particular, on the DBLP dataset with 14.3k nodes, Cella is able to achieve an 8.08% conspicuous improvement in accuracy over the state-of-the-art at a cost of less than one cent.

[Arxiv](https://arxiv.org/abs/2412.11983)