# 自动注释增强：助力分子与自然语言之间的高效翻译

发布时间：2025年02月10日

`LLM应用` `药物研发` `生物信息学`

> Automatic Annotation Augmentation Boosts Translation between Molecules and Natural Language

# 摘要

> AI在生物研究领域的最新进展着重于整合分子数据与自然语言，以加速药物研发进程。然而，高质量标注数据的匮乏仍是该领域的主要瓶颈。本文提出了一种名为LA$^3$的基于语言的自动标注增强框架，通过利用大型语言模型增强现有数据集，从而显著提升AI训练效果。我们通过构建增强数据集LaChEBI-20来验证LA$^3$的实际效果，在此数据集中，我们系统性地重写了来自现有数据集的分子标注。这些重写后的标注不仅保留了关键的分子信息，还提供了更加丰富多样的句式结构和词汇表达。基于LaChEBI-20数据集，我们训练了基于基准架构的LaMolT5模型，使其能够有效学习分子表示与增强标注之间的映射关系。在基于文本的*de novo*分子生成和分子描述任务上的实验结果表明，LaMolT5的表现显著优于现有最优模型。特别值得一提的是，引入LA$^3$后，模型性能较基准架构提升了高达301%。此外，我们还验证了LA$^3$在*图像*、*文本*和*图*任务中的有效性，进一步证明了其多样性和实用性。

> Recent advancements in AI for biological research focus on integrating molecular data with natural language to accelerate drug discovery. However, the scarcity of high-quality annotations limits progress in this area. This paper introduces LA$^3$, a Language-based Automatic Annotation Augmentation framework that leverages large language models to augment existing datasets, thereby improving AI training. We demonstrate the effectiveness of LA$^3$ by creating an enhanced dataset, LaChEBI-20, where we systematically rewrite the annotations of molecules from an established dataset. These rewritten annotations preserve essential molecular information while providing more varied sentence structures and vocabulary. Using LaChEBI-20, we train LaMolT5 based on a benchmark architecture to learn the mapping between molecular representations and augmented annotations.
  Experimental results on text-based *de novo* molecule generation and molecule captioning demonstrate that LaMolT5 outperforms state-of-the-art models. Notably, incorporating LA$^3$ leads to improvements of up to 301% over the benchmark architecture. Furthermore, we validate the effectiveness of LA$^3$ notable applications in *image*, *text* and *graph* tasks, affirming its versatility and utility.

[Arxiv](https://arxiv.org/abs/2502.06634)