# 基于大型语言模型的语义一致性正则化在半监督情感分析中的应用

发布时间：2025年01月29日

`LLM应用

理由：该论文摘要描述了一种基于大型语言模型（LLMs）的语义一致性正则化（SCR）框架，用于半监督情感分析任务。该方法利用LLMs的能力来增强数据，并通过一致性损失计算和置信度阈值来提供额外的监督信号。这表明该研究主要关注如何将LLMs应用于具体的情感分析任务，属于LLM应用的范畴。` `情感分析` `客户反馈`

> Semantic Consistency Regularization with Large Language Models for Semi-supervised Sentiment Analysis

# 摘要

> # 摘要
准确的文本情感分析在理解客户反馈、监控市场趋势和检测公众情绪等方面至关重要。然而，手动标注大规模情感语料库用于监督学习既费时又费力。因此，开发一种半监督方法用于情感分析任务既必要又有效。尽管已有一些半监督文本分类方法，但它们依赖于未标注数据的内在信息和NLP模型的学习能力，在情感分析场景中缺乏泛化能力且容易过拟合。受预训练大型语言模型（LLMs）在遵循指令和生成连贯文本方面的能力启发，我们提出了一种基于LLMs的语义一致性正则化（SCR）框架，用于半监督情感分析。我们引入了两种提示策略：基于实体的增强（SCR-EE）和基于概念的增强（SCR-CE）。SCR-EE通过提取实体和数值信息，并查询LLM重建文本信息；SCR-CE则直接使用原始句子查询LLM进行语义重建。随后，利用LLM增强的数据进行一致性损失计算，并通过置信度阈值保留高质量一致样本，以在训练过程中提供额外的监督信号。此外，为了充分利用不确定的未标注数据样本，我们提出了一种受类空间收缩定理启发的类重组策略。实验表明，我们的方法在之前的半监督方法中取得了显著的性能提升。

> Accurate sentiment analysis of texts is crucial for a variety of applications, such as understanding customer feedback, monitoring market trends, and detecting public sentiment. However, manually annotating large sentiment corpora for supervised learning is labor-intensive and time-consuming. Therefore, it is essential and effective to develop a semi-supervised method for the sentiment analysis task. Although some methods have been proposed for semi-supervised text classification, they rely on the intrinsic information within the unlabeled data and the learning capability of the NLP model, which lack generalization ability to the sentiment analysis scenario and may prone to overfit. Inspired by the ability of pretrained Large Language Models (LLMs) in following instructions and generating coherent text, we propose a Semantic Consistency Regularization with Large Language Models (SCR) framework for semi-supervised sentiment analysis. We introduce two prompting strategies to semantically enhance unlabeled text using LLMs. The first is Entity-based Enhancement (SCR-EE), which involves extracting entities and numerical information, and querying the LLM to reconstruct the textual information. The second is Concept-based Enhancement (SCR-CE), which directly queries the LLM with the original sentence for semantic reconstruction. Subsequently, the LLM-augmented data is utilized for a consistency loss with confidence thresholding, which preserves high-quality agreement samples to provide additional supervision signals during training. Furthermore, to fully utilize the uncertain unlabeled data samples, we propose a class re-assembling strategy inspired by the class space shrinking theorem. Experiments show our method achieves remarkable performance over prior semi-supervised methods.

[Arxiv](https://arxiv.org/abs/2501.17598)