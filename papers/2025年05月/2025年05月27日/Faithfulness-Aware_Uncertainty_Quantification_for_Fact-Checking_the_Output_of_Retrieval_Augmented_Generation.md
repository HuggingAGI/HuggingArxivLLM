# # 摘要  
    针对检索增强生成输出的事实核查，提出了一种保真度感知的不确定性量化方法。

发布时间：2025年05月27日

`RAG` `问答系统` `信息检索`

> Faithfulness-Aware Uncertainty Quantification for Fact-Checking the Output of Retrieval Augmented Generation

# 摘要

> 大型语言模型（LLMs）通过检索增强生成（RAG）方法在开放领域问答中表现出色，但RAG系统仍易产生幻觉，即由于模型知识不一致或上下文使用不当导致的事实错误输出。现有方法常将事实性与上下文忠实性混淆，导致事实正确但未直接支持的陈述被误判为幻觉。本文提出FRANQ（基于忠实性的检索增强不确定性量化），通过评估陈述是否忠实于检索到的上下文来检测幻觉。我们还引入了新的长格式问答数据集，结合自动化标注与人工验证，标注事实性和忠实性。实验显示，FRANQ在检测RAG生成响应中的事实错误方面优于现有方法。

> Large Language Models (LLMs) enhanced with external knowledge retrieval, an approach known as Retrieval-Augmented Generation (RAG), have shown strong performance in open-domain question answering. However, RAG systems remain susceptible to hallucinations: factually incorrect outputs that may arise either from inconsistencies in the model's internal knowledge or incorrect use of the retrieved context. Existing approaches often conflate factuality with faithfulness to the retrieved context, misclassifying factually correct statements as hallucinations if they are not directly supported by the retrieval. In this paper, we introduce FRANQ (Faithfulness-based Retrieval Augmented UNcertainty Quantification), a novel method for hallucination detection in RAG outputs. FRANQ applies different Uncertainty Quantification (UQ) techniques to estimate factuality based on whether a statement is faithful to the retrieved context or not. To evaluate FRANQ and other UQ techniques for RAG, we present a new long-form Question Answering (QA) dataset annotated for both factuality and faithfulness, combining automated labeling with manual validation of challenging examples. Extensive experiments on long- and short-form QA across multiple datasets and LLMs show that FRANQ achieves more accurate detection of factual errors in RAG-generated responses compared to existing methods.

[Arxiv](https://arxiv.org/abs/2505.21072)