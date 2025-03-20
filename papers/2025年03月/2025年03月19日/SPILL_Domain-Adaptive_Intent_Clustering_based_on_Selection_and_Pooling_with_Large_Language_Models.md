# 基于选择与汇聚机制的大语言模型领域自适应意图聚类：SPILL方法研究

发布时间：2025年03月19日

`LLM应用` `意图聚类`

> SPILL: Domain-Adaptive Intent Clustering based on Selection and Pooling with Large Language Models

# 摘要

> 在本文中，我们提出了一种名为 SPILL（Selection and Pooling with Large Language Models，基于大型语言模型的选择与汇聚）的直观且具有领域适应性的方法，用于无需微调的意图聚类。现有的基于嵌入的聚类方法依赖于少量标注示例或无监督微调来优化每个新数据集的结果，这使得它们在多个数据集上的泛化能力较弱。我们的目标是使这些现有的嵌入器在无需进一步微调的情况下更具跨领域数据集的泛化能力。

受我们在采样和汇聚技术有效性方面的理论推导和模拟结果的启发，我们将聚类任务视为一个小规模的选择问题。这一问题的良好解决方案与更优的聚类性能相关联。据此，我们提出了一种两阶段方法：首先，对于每个 utterance（称为种子），我们使用现有的嵌入器导出其嵌入。然后，我们应用距离度量从候选池中选择与种子接近的候选。由于嵌入器并未针对新数据集进行优化，在第二阶段，我们使用大型语言模型（LLM）从这些候选中进一步选择与种子具有相同意图的 utterance。最后，我们将这些选定的候选与种子汇聚，以导出种子的精炼嵌入。

我们发现，我们的方法通常优于直接使用嵌入器，并且在与其它最先进的研究相比，甚至那些使用更大模型并需要微调的研究相比，我们的方法也能达到可比的结果，这表明了它的优势和效率。我们的结果表明，我们的方法使现有的嵌入器在无需额外微调的情况下进一步改进，使其更具适应性以应对新的领域数据集。此外，将聚类任务视为一个小规模的选择问题，为根据用户目标利用 LLM 定制聚类任务提供了潜力。

> In this paper, we propose Selection and Pooling with Large Language Models (SPILL), an intuitive and domain-adaptive method for intent clustering without fine-tuning. Existing embeddings-based clustering methods rely on a few labeled examples or unsupervised fine-tuning to optimize results for each new dataset, which makes them less generalizable to multiple datasets. Our goal is to make these existing embedders more generalizable to new domain datasets without further fine-tuning. Inspired by our theoretical derivation and simulation results on the effectiveness of sampling and pooling techniques, we view the clustering task as a small-scale selection problem. A good solution to this problem is associated with better clustering performance. Accordingly, we propose a two-stage approach: First, for each utterance (referred to as the seed), we derive its embedding using an existing embedder. Then, we apply a distance metric to select a pool of candidates close to the seed. Because the embedder is not optimized for new datasets, in the second stage, we use an LLM to further select utterances from these candidates that share the same intent as the seed. Finally, we pool these selected candidates with the seed to derive a refined embedding for the seed. We found that our method generally outperforms directly using an embedder, and it achieves comparable results to other state-of-the-art studies, even those that use much larger models and require fine-tuning, showing its strength and efficiency. Our results indicate that our method enables existing embedders to be further improved without additional fine-tuning, making them more adaptable to new domain datasets. Additionally, viewing the clustering task as a small-scale selection problem gives the potential of using LLMs to customize clustering tasks according to the user's goals.

[Arxiv](https://arxiv.org/abs/2503.15351)