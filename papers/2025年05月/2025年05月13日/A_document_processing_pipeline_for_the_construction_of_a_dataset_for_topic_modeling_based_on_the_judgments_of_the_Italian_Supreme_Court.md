# # 基于意大利最高法院判决构建主题模型数据集的文档处理流水线

发布时间：2025年05月13日

`LLM应用` `主题建模`

> A document processing pipeline for the construction of a dataset for topic modeling based on the judgments of the Italian Supreme Court

# 摘要

> 意大利法律研究中的主题建模因缺乏公开数据集而受限，这使得对最高法院判决中法律主题的分析变得困难。为了解决这一问题，我们开发了一个文档处理管道，生成了一个经过匿名化处理且专门优化用于主题建模的数据集。
    该管道集成了文档布局分析（YOLOv8x）、光学字符识别和文本匿名化功能。DLA 模块在 mAP@50 上达到了 0.964，在 mAP@50-95 上达到了 0.800。OCR 检测器在 mAP@50-95 上达到了 0.9022，而文本识别器（TrOCR）的字符错误率为 0.0047，单词错误率为 0.0248。与仅使用 OCR 的方法相比，我们的数据集在主题建模方面表现更优，其多样性得分为 0.6198，连贯性得分为 0.6638。
    我们采用 BERTopic 进行主题提取，并利用大型语言模型生成标签和摘要。输出结果与领域专家的解读进行了对比评估。Claude Sonnet 3.7 在标签生成方面达到了 0.8119 的 BERTScore F1 值，在摘要生成方面达到了 0.9130 的 F1 值。

> Topic modeling in Italian legal research is hindered by the lack of public datasets, limiting the analysis of legal themes in Supreme Court judgments. To address this, we developed a document processing pipeline that produces an anonymized dataset optimized for topic modeling.
  The pipeline integrates document layout analysis (YOLOv8x), optical character recognition, and text anonymization. The DLA module achieved a mAP@50 of 0.964 and a mAP@50-95 of 0.800. The OCR detector reached a mAP@50-95 of 0.9022, and the text recognizer (TrOCR) obtained a character error rate of 0.0047 and a word error rate of 0.0248. Compared to OCR-only methods, our dataset improved topic modeling with a diversity score of 0.6198 and a coherence score of 0.6638.
  We applied BERTopic to extract topics and used large language models to generate labels and summaries. Outputs were evaluated against domain expert interpretations. Claude Sonnet 3.7 achieved a BERTScore F1 of 0.8119 for labeling and 0.9130 for summarization.

[Arxiv](https://arxiv.org/abs/2505.08439)