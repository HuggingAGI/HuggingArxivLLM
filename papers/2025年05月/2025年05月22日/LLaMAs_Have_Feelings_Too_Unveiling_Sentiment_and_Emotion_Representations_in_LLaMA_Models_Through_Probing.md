# # LLaMA也有情感世界：探查模型中的情感与情绪表示

发布时间：2025年05月22日

`LLM应用` `情感分析`

> LLaMAs Have Feelings Too: Unveiling Sentiment and Emotion Representations in LLaMA Models Through Probing

# 摘要

> 大型语言模型（LLMs）迅速成为自然语言处理（NLP）领域的核心，通过提示工程技术，它们能够适应多种任务，包括情感分析。然而，我们对这些模型如何捕捉情感相关信息的理解仍然有限。本研究深入探索了Llama模型的隐藏层，旨在确定情感特征最集中的位置，并评估其对情感分析的影响。

通过探针分类器，我们分析了不同层和尺度的情感编码，识别出最能捕捉情感信号的层和池化方法。我们的结果显示，在二元情感极性任务中，情感信息主要集中在中间层，与提示工程技术相比，检测准确率提高了14%。此外，我们发现，在仅解码器模型中，最后一个标记并非始终是情感编码最有信息量的部分。最后，这种方法使情感任务的内存需求平均减少了57%。

这些见解有助于更全面地理解LLMs中的情感表示，建议采用特定层的探针方法作为情感任务的有效替代方案，不仅超越了传统的提示工程技术，还具有提升模型实用性和降低内存需求的潜力。

> Large Language Models (LLMs) have rapidly become central to NLP, demonstrating their ability to adapt to various tasks through prompting techniques, including sentiment analysis. However, we still have a limited understanding of how these models capture sentiment-related information. This study probes the hidden layers of Llama models to pinpoint where sentiment features are most represented and to assess how this affects sentiment analysis.
  Using probe classifiers, we analyze sentiment encoding across layers and scales, identifying the layers and pooling methods that best capture sentiment signals. Our results show that sentiment information is most concentrated in mid-layers for binary polarity tasks, with detection accuracy increasing up to 14% over prompting techniques. Additionally, we find that in decoder-only models, the last token is not consistently the most informative for sentiment encoding. Finally, this approach enables sentiment tasks to be performed with memory requirements reduced by an average of 57%.
  These insights contribute to a broader understanding of sentiment in LLMs, suggesting layer-specific probing as an effective approach for sentiment tasks beyond prompting, with potential to enhance model utility and reduce memory requirements.

[Arxiv](https://arxiv.org/abs/2505.16491)