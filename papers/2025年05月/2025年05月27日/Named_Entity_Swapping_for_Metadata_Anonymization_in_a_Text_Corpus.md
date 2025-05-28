# 在文本语料库中进行元数据匿名化的命名实体交换方法

发布时间：2025年05月27日

`LLM应用` `数据隐私`

> Named Entity Swapping for Metadata Anonymization in a Text Corpus

# 摘要

> 本研究提出了一种针对文本语料库的匿名化方案，旨在保护元数据不被泄露，特别是防止大型语言模型识别与文本相关的元数据，从而避免这些元数据对查询响应产生影响。该方案的核心机制是“命名实体交换”，这一技术灵感来源于统计披露控制中的数据交换方法。我们的方法基于嵌入向量的相似性，从不同文本中随机选择语义相似的子字符串对，并在它们之间交换部分命名实体，从而防止某些命名实体的组合与特定文本的元数据唯一关联。我们的方法具有两大优势：首先，用户可以通过调整几个关键决策变量，找到数据效用和数据风险之间的最佳平衡点，从而确定最优的匿名化程度；其次，我们的方法利用文本嵌入技术来计算交换权重并评估数据效用，这使得整个工作流程具有高度的灵活性和定制化能力。我们通过一个实际应用案例展示了该方法的有效性，该案例成功防止了公司名称在 earnings call 会议记录的横截面数据集中被披露。

> This work introduces an anonymization scheme for a corpus of texts to safeguard metadata from disclosure. It specifically aims to prevent large language models from identifying metadata associated with texts, thereby avoiding their influence on query responses. The core mechanism is called named entity swapping, a technique inspired by data swapping in statistical disclosure control. Our method randomly selects pairs of semantically similar substrings from different texts based on the similarity of their embedding vectors and interchanges some named entities between them. This prevents certain combinations of named entities from being uniquely associated with the metadata of individual texts. Our approach offers two key advantages. First, it enables users to determine the optimal level of anonymization that balances data utility and data risk through a calibration of several key decision variables. Second, it leverages text embeddings both to compute swapping weights and to assess data utility, enabling a high degree of flexibility and customization in the overall workflow. The effectiveness of the proposed method is demonstrated with an application that prevents the disclosure of company names in a cross-sectional dataset of earnings call transcripts.

[Arxiv](https://arxiv.org/abs/2505.21128)