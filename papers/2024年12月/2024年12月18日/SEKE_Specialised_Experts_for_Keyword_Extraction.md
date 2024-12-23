# SEKE：关键词提取的专业行家

发布时间：2024年12月18日

`LLM应用` `文本分类`

> SEKE: Specialised Experts for Keyword Extraction

# 摘要

> 关键字提取旨在找出文档中最具描述性的词汇，从而实现对大量多样文本数据的自动分类与总结。基于现实中关键字检测往往需要处理多样内容这一认识，我们提出了一种基于专家混合（MoE）技术的新型有监督关键字提取方法。MoE利用可学习的路由子网络将信息导向专业专家，让他们专注于输入空间的不同区域。SEKE，即用于有监督关键字提取的专业专家混合，以DeBERTa为骨干模型，构建于MoE框架之上，专家关注每个标记，并通过与递归神经网络（RNN）集成，即使在较小的语料库上（因缺乏训练数据而更难实现专业化）也能成功提取。MoE框架还能洞察各个专家的内部运作，增强了该方法的可解释性。我们在多个英语数据集上对SEKE进行基准测试，其性能达到了最先进水平，优于强大的有监督和无监督基线。我们的分析显示，根据数据的大小和类型，专家会专注于不同的句法和语义成分，比如标点、停用词、词性或命名实体。代码获取地址：https://github.com/matejMartinc/SEKE_keyword_extraction 。

> Keyword extraction involves identifying the most descriptive words in a document, allowing automatic categorisation and summarisation of large quantities of diverse textual data. Relying on the insight that real-world keyword detection often requires handling of diverse content, we propose a novel supervised keyword extraction approach based on the mixture of experts (MoE) technique. MoE uses a learnable routing sub-network to direct information to specialised experts, allowing them to specialize in distinct regions of the input space. SEKE, a mixture of Specialised Experts for supervised Keyword Extraction, uses DeBERTa as the backbone model and builds on the MoE framework, where experts attend to each token, by integrating it with a recurrent neural network (RNN), to allow successful extraction even on smaller corpora, where specialisation is harder due to lack of training data. The MoE framework also provides an insight into inner workings of individual experts, enhancing the explainability of the approach. We benchmark SEKE on multiple English datasets, achieving state-of-the-art performance compared to strong supervised and unsupervised baselines. Our analysis reveals that depending on data size and type, experts specialize in distinct syntactic and semantic components, such as punctuation, stopwords, parts-of-speech, or named entities. Code is available at: https://github.com/matejMartinc/SEKE_keyword_extraction

[Arxiv](https://arxiv.org/abs/2412.14087)