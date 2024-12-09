# 大型语言模型能否在工业规模下成为科学文献分层多标签分类的有效分类器？

发布时间：2024年12月06日

`LLM应用` `文献分类`

> Can Large Language Models Serve as Effective Classifiers for Hierarchical Multi-Label Classification of Scientific Documents at Industrial Scale?

# 摘要

> 我们致力于解决工业规模下科学文献的分层多标签分类（HMC）任务，在这一任务中，需要对数以万计的文档按照成千上万的动态标签进行分类。科学出版物的快速增长，使得可扩展且高效的分类方法成为必需，而分类法不断演变——新类别出现、现有类别合并以及过时类别淘汰——让情况更为复杂。传统的机器学习方法，由于每次分类法更新都需要耗费大量成本重新训练，且标记数据收集和模型适配的开销巨大，变得不切实际。大型语言模型（LLMs）在诸如多标签分类这样的复杂任务中展现出巨大潜力。然而，将其应用于大规模且动态的分类法时，面临着独特的挑战，因为标签数量众多，可能超出 LLMs 的输入限制。在本文中，我们提出了将 LLMs 的优势与密集检索技术相结合的新颖方法，以应对这些挑战。我们的方法借助零样本 HMC 实现实时标签分配，从而避免了重新训练。我们在 SSRN（一个涵盖多学科的大型预印本库）上对我们的方法进行了有效性评估，在分类准确性和成本效益方面均取得了显著提升。通过为动态分类法开发定制的评估框架并公开我们的代码，本研究为在工业规模上应用 LLMs 进行文档分类（其中类别数量对应于大型分类法中的节点数量）提供了重要的见解。

> We address the task of hierarchical multi-label classification (HMC) of scientific documents at an industrial scale, where hundreds of thousands of documents must be classified across thousands of dynamic labels. The rapid growth of scientific publications necessitates scalable and efficient methods for classification, further complicated by the evolving nature of taxonomies--where new categories are introduced, existing ones are merged, and outdated ones are deprecated. Traditional machine learning approaches, which require costly retraining with each taxonomy update, become impractical due to the high overhead of labelled data collection and model adaptation. Large Language Models (LLMs) have demonstrated great potential in complex tasks such as multi-label classification. However, applying them to large and dynamic taxonomies presents unique challenges as the vast number of labels can exceed LLMs' input limits. In this paper, we present novel methods that combine the strengths of LLMs with dense retrieval techniques to overcome these challenges. Our approach avoids retraining by leveraging zero-shot HMC for real-time label assignment. We evaluate the effectiveness of our methods on SSRN, a large repository of preprints spanning multiple disciplines, and demonstrate significant improvements in both classification accuracy and cost-efficiency. By developing a tailored evaluation framework for dynamic taxonomies and publicly releasing our code, this research provides critical insights into applying LLMs for document classification, where the number of classes corresponds to the number of nodes in a large taxonomy, at an industrial scale.

[Arxiv](https://arxiv.org/abs/2412.05137)