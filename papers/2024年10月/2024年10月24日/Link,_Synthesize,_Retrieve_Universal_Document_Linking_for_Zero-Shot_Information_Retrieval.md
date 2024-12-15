# 链接、合成、检索：零样本信息检索的通用文档链接方式

发布时间：2024年10月24日

`其他` `信息检索` `零样本学习`

> Link, Synthesize, Retrieve: Universal Document Linking for Zero-Shot Information Retrieval

# 摘要

> 尽管信息检索（IR）近来有所进步，可零样本 IR 依旧是个重大挑战，特别是在应对新领域、新语言以及新发布的用例时，这些用例缺少现有用户的历史查询流量。针对这类情况，常见做法是先进行查询增强，然后基于与合成查询配对的文档数据对预训练模型进行微调。在本研究中，我们提出了一种新颖的通用文档链接（UDL）算法，它能链接相似文档，从而在多个不同特征的数据集上增强合成查询的生成。UDL 借助熵来选择相似性模型，并通过相似性得分利用命名实体识别（NER）来决定文档的链接。我们的实证研究表明，UDL 在不同数据集和 IR 模型中具有有效性和通用性，在零样本情况下超越了最先进的方法。用于重现的开发代码可在 https://github.com/eoduself/UDL 中获取。

> Despite the recent advancements in information retrieval (IR), zero-shot IR remains a significant challenge, especially when dealing with new domains, languages, and newly-released use cases that lack historical query traffic from existing users. For such cases, it is common to use query augmentations followed by fine-tuning pre-trained models on the document data paired with synthetic queries. In this work, we propose a novel Universal Document Linking (UDL) algorithm, which links similar documents to enhance synthetic query generation across multiple datasets with different characteristics. UDL leverages entropy for the choice of similarity models and named entity recognition (NER) for the link decision of documents using similarity scores. Our empirical studies demonstrate the effectiveness and universality of the UDL across diverse datasets and IR models, surpassing state-of-the-art methods in zero-shot cases. The developed code for reproducibility is included in https://github.com/eoduself/UDL

[Arxiv](https://arxiv.org/abs/2410.18385)