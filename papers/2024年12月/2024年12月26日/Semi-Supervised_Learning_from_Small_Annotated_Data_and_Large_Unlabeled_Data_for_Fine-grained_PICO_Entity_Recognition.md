# 基于小规模标注数据和大规模未标注数据的半监督学习用于细粒度PICO实体识别

发布时间：2024年12月26日

`LLM应用

理由：这篇论文主要讨论了如何利用半监督学习方法开发一个命名实体识别（NER）模型，用于从临床试验文献中提取细粒度的PICO元素。虽然论文没有明确提到使用大型语言模型（LLM），但NER任务通常与自然语言处理（NLP）相关，而LLM在NLP任务中的应用非常广泛。因此，这篇论文可以被归类为LLM应用，因为它涉及到了NLP任务中的模型开发和应用。` `临床试验`

> Semi-Supervised Learning from Small Annotated Data and Large Unlabeled Data for Fine-grained PICO Entity Recognition

# 摘要

> # 目标
从临床试验文献中提取PICO元素（参与者、干预措施、比较和结果）对临床证据的检索、评估和综合至关重要。现有方法未能区分PICO实体的属性。本研究旨在开发一个命名实体识别（NER）模型，用于提取细粒度的PICO实体。

# 材料与方法
我们使用来自4个公共数据集的2511篇包含PICO提及的摘要，开发了一种半监督方法，结合少量标注数据和大量未标注数据，训练NER模型FinePICO。我们将数据集分为小标注子集和大未标注子集，并基于仅在小标注子集上训练的监督学习模型和在整个标注集上训练的模型，分别建立性能下限和上限。最后，我们在两个子集上评估FinePICO，使用精确率、召回率和F1分数衡量其性能。

# 结果
我们的方法在使用少量标注样本时，精确率/召回率/F1分数分别达到0.567/0.636/0.60，比基线模型（F1: 0.437）高出16%以上。该模型在不同PICO框架和语料库上表现出泛化能力，在各种实验设置中始终优于基准（p值<0.001）。

# 结论
本研究提出了一种通用且有效的半监督命名实体识别方法，利用大量未标注数据和小量标注数据，初步支持了细粒度的PICO提取。

> Objective: Extracting PICO elements -- Participants, Intervention, Comparison, and Outcomes -- from clinical trial literature is essential for clinical evidence retrieval, appraisal, and synthesis. Existing approaches do not distinguish the attributes of PICO entities. This study aims to develop a named entity recognition (NER) model to extract PICO entities with fine granularities.
  Materials and Methods: Using a corpus of 2,511 abstracts with PICO mentions from 4 public datasets, we developed a semi-supervised method to facilitate the training of a NER model, FinePICO, by combining limited annotated data of PICO entities and abundant unlabeled data. For evaluation, we divided the entire dataset into two subsets: a smaller group with annotations and a larger group without annotations. We then established the theoretical lower and upper performance bounds based on the performance of supervised learning models trained solely on the small, annotated subset and on the entire set with complete annotations, respectively. Finally, we evaluated FinePICO on both the smaller annotated subset and the larger, initially unannotated subset. We measured the performance of FinePICO using precision, recall, and F1.
  Results: Our method achieved precision/recall/F1 of 0.567/0.636/0.60, respectively, using a small set of annotated samples, outperforming the baseline model (F1: 0.437) by more than 16\%. The model demonstrates generalizability to a different PICO framework and to another corpus, which consistently outperforms the benchmark in diverse experimental settings (p-value \textless0.001).
  Conclusion: This study contributes a generalizable and effective semi-supervised approach to named entity recognition leveraging large unlabeled data together with small, annotated data. It also initially supports fine-grained PICO extraction.

[Arxiv](https://arxiv.org/abs/2412.19346)