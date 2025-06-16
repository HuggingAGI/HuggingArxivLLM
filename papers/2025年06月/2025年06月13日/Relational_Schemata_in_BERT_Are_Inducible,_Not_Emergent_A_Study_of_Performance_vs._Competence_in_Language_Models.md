# BERT中的关系模式是可诱导而非涌现的：一项关于语言模型表现与能力的研究

发布时间：2025年06月13日

`LLM理论` `人工智能`

> Relational Schemata in BERT Are Inducible, Not Emergent: A Study of Performance vs. Competence in Language Models

# 摘要

> 尽管像BERT这样的大型语言模型在语义任务中表现出色，但这种表现是否反映了真正意义上的概念理解能力，还是仅仅体现了表层的统计关联，尚不明确。我通过分析BERT在 taxonomy（分类学）、mereology（整体论）和 functionality（功能）三种关系下概念对的内部表示，研究了BERT是否编码了抽象的关系模式。我还对比了BERT在关系分类任务中的表现与[CLS]标记嵌入的表征结构。实验结果显示，预训练的BERT在关系分类任务中表现优异，分类准确率极高，这表明模型内部蕴含着潜在的关系信号。然而，只有在经过监督式关系分类任务的微调后，概念对才会按照关系类型在高维嵌入空间中形成组织。这表明，关系模式并非仅凭预训练就能自发形成，而是可以通过任务支架来引导模型学习。这些发现揭示了模型的行为表现并不必然意味着其具备结构化的概念理解能力，尽管通过适当的训练，模型可以习得针对具体关系的归纳偏置，从而实现基于经验的关系抽象。

> While large language models like BERT demonstrate strong empirical performance on semantic tasks, whether this reflects true conceptual competence or surface-level statistical association remains unclear. I investigate whether BERT encodes abstract relational schemata by examining internal representations of concept pairs across taxonomic, mereological, and functional relations. I compare BERT's relational classification performance with representational structure in [CLS] token embeddings. Results reveal that pretrained BERT enables high classification accuracy, indicating latent relational signals. However, concept pairs organize by relation type in high-dimensional embedding space only after fine-tuning on supervised relation classification tasks. This indicates relational schemata are not emergent from pretraining alone but can be induced via task scaffolding. These findings demonstrate that behavioral performance does not necessarily imply structured conceptual understanding, though models can acquire inductive biases for grounded relational abstraction through appropriate training.

[Arxiv](https://arxiv.org/abs/2506.11485)