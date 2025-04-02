# # GLiNER-biomed：一套高效实用的开放生物医学命名实体识别模型套装

发布时间：2025年04月01日

`LLM应用` `生物医学`

> GLiNER-biomed: A Suite of Efficient Models for Open Biomedical Named Entity Recognition

# 摘要

> 生物医学命名实体识别（NER）面临独特挑战，原因在于其专业的术语、庞大的实体数量以及不断涌现的新实体。传统NER模型受限于固定的分类体系和人工标注，难以突破预定义实体类型进行泛化，也无法高效适应新概念。为解决这些问题，我们推出GLiNER-biomed，这是针对生物医学NER的领域自适应版通用轻量NER模型套件。与传统方法不同，GLiNER采用自然语言描述推断任意实体类型，从而实现零样本识别。我们的方法首先将大型语言模型（LLMs）的标注能力精简到一个更小、更高效的模型中，从而生成覆盖广泛的合成生物医学NER数据。随后，我们训练两种GLiNER架构——单编码器和双编码器——在多个规模上进行平衡计算效率与识别性能。在多个生物医学数据集上的评估表明，GLiNER-biomed在零样本和少样本场景下均优于现有的GLiNER模型，F1分数提升了5.96%。消融实验突显了我们的合成数据生成策略的有效性，并强调了生物医学预训练与高质量通用领域标注微调相结合的互补优势。所有数据集、模型和训练管道均可在https://github.com/ds4dh/GLiNER-biomed公开获取。

> Biomedical named entity recognition (NER) presents unique challenges due to specialized vocabularies, the sheer volume of entities, and the continuous emergence of novel entities. Traditional NER models, constrained by fixed taxonomies and human annotations, struggle to generalize beyond predefined entity types or efficiently adapt to emerging concepts. To address these issues, we introduce GLiNER-biomed, a domain-adapted suite of Generalist and Lightweight Model for NER (GLiNER) models specifically tailored for biomedical NER. In contrast to conventional approaches, GLiNER uses natural language descriptions to infer arbitrary entity types, enabling zero-shot recognition. Our approach first distills the annotation capabilities of large language models (LLMs) into a smaller, more efficient model, enabling the generation of high-coverage synthetic biomedical NER data. We subsequently train two GLiNER architectures, uni- and bi-encoder, at multiple scales to balance computational efficiency and recognition performance. Evaluations on several biomedical datasets demonstrate that GLiNER-biomed outperforms state-of-the-art GLiNER models in both zero- and few-shot scenarios, achieving 5.96% improvement in F1-score over the strongest baseline. Ablation studies highlight the effectiveness of our synthetic data generation strategy and emphasize the complementary benefits of synthetic biomedical pre-training combined with fine-tuning on high-quality general-domain annotations. All datasets, models, and training pipelines are publicly available at https://github.com/ds4dh/GLiNER-biomed.

[Arxiv](https://arxiv.org/abs/2504.00676)