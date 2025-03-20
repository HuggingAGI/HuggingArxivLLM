# TROVE：通过源句追踪与关系分类探索细粒度文本溯源的挑战

发布时间：2025年03月19日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在文本生成中的实际应用，特别是通过TROVE挑战来追溯内容来源和分析生成过程。它涉及LLMs在特定任务中的性能评估和应用，属于应用层面的研究。` `问答系统` `文本摘要`

> TROVE: A Challenge for Fine-Grained Text Provenance via Source Sentence Tracing and Relationship Classification

# 摘要

> 尽管大型语言模型（LLMs）在文本生成方面表现优异，但其广泛应用引发了对内容可靠性和问责制的担忧。在医疗、法律和新闻等高风险领域，理解内容的来源和生成方式至关重要。为此，我们提出了文本溯源（TROVE）挑战，旨在将目标文本中的每一句话追溯到潜在长文本或多文档输入中的具体源句。TROVE不仅能够识别来源，还对细粒度关系（如引用、压缩、推理等）进行标注，从而深入了解每个目标句子的形成过程。为评估TROVE，我们构建了一个包含三个公共数据集的基准数据集，涵盖了11种多样的场景（如问答和摘要），覆盖了中英文，源文本长度从0-5k、5-10k到10k+不等，特别强调了对溯源至关重要的多文档和长文档设置。为确保数据质量，我们采用了三阶段标注流程：句子检索、GPT溯源和人工溯源。我们评估了11种LLMs在直接提示和检索增强范式下的表现，发现检索对于稳健性能至关重要，大型模型在复杂关系分类中表现更优，而闭源模型往往领先，开源模型则展现出巨大潜力，特别是在检索增强的情况下。

> LLMs have achieved remarkable fluency and coherence in text generation, yet their widespread adoption has raised concerns about content reliability and accountability. In high-stakes domains such as healthcare, law, and news, it is crucial to understand where and how the content is created. To address this, we introduce the Text pROVEnance (TROVE) challenge, designed to trace each sentence of a target text back to specific source sentences within potentially lengthy or multi-document inputs. Beyond identifying sources, TROVE annotates the fine-grained relationships (quotation, compression, inference, and others), providing a deep understanding of how each target sentence is formed. To benchmark TROVE, we construct our dataset by leveraging three public datasets covering 11 diverse scenarios (e.g., QA and summarization) in English and Chinese, spanning source texts of varying lengths (0-5k, 5-10k, 10k+), emphasizing the multi-document and long-document settings essential for provenance. To ensure high-quality data, we employ a three-stage annotation process: sentence retrieval, GPT provenance, and human provenance. We evaluate 11 LLMs under direct prompting and retrieval-augmented paradigms, revealing that retrieval is essential for robust performance, larger models perform better in complex relationship classification, and closed-source models often lead, yet open-source models show significant promise, particularly with retrieval augmentation.

[Arxiv](https://arxiv.org/abs/2503.15289)