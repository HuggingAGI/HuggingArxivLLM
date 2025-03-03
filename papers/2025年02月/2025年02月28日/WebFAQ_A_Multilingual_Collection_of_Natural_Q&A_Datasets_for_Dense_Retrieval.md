# WebFAQ：一个多语言自然问答数据集集合，专为密集检索设计。

发布时间：2025年02月28日

`LLM应用` `问答系统` `多语言处理`

> WebFAQ: A Multilingual Collection of Natural Q&A Datasets for Dense Retrieval

# 摘要

> 我们推出了WebFAQ，这是一个基于FAQ风格schema.org标注的大型开放领域问答数据集。该数据集涵盖75种语言，包含9600万个自然问答对，其中4700万个为非英语样本（占49%）。WebFAQ还支持20个单语检索基准，总规模达1120万个问答对（其中590万个为非英语）。这些数据集经过精心筛选和近重复检测，为多语言密集检索模型的训练和评估提供了高质量资源。为了验证WebFAQ的实际效果，我们使用这些问答对对XLM-RoBERTa模型进行了领域内微调。通过这种针对性的微调，模型在检索性能上取得了显著提升，这种优势不仅体现在WebFAQ上，还推广到了其他多语言检索基准的零样本评估中。此外，我们利用WebFAQ构建了一组涵盖1000多种语言对的问答对齐双语语料库，采用了先进的双文本挖掘和自动化LLM评估翻译方法。得益于我们创新的自动化双文本数据集生成方法，这些双语语料库在翻译质量上超越了现有类似数据集。WebFAQ及所有相关资源现已在GitHub和HuggingFace上公开发布。

> We present WebFAQ, a large-scale collection of open-domain question answering datasets derived from FAQ-style schema.org annotations. In total, the data collection consists of 96 million natural question-answer (QA) pairs across 75 languages, including 47 million (49%) non-English samples. WebFAQ further serves as the foundation for 20 monolingual retrieval benchmarks with a total size of 11.2 million QA pairs (5.9 million non-English). These datasets are carefully curated through refined filtering and near-duplicate detection, yielding high-quality resources for training and evaluating multilingual dense retrieval models. To empirically confirm WebFAQ's efficacy, we use the collected QAs to fine-tune an in-domain pretrained XLM-RoBERTa model. Through this process of dataset-specific fine-tuning, the model achieves significant retrieval performance gains, which generalize - beyond WebFAQ - to other multilingual retrieval benchmarks evaluated in zero-shot setting. Last but not least, we utilize WebFAQ to construct a set of QA-aligned bilingual corpora spanning over 1000 language pairs using state-of-the-art bitext mining and automated LLM-assessed translation evaluation. Due to our advanced, automated method of bitext dataset generation, the resulting bilingual corpora demonstrate higher translation quality compared to similar datasets. WebFAQ and all associated resources are publicly available on GitHub and HuggingFace.

[Arxiv](https://arxiv.org/abs/2502.20936)