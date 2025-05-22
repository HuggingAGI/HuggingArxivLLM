# 倾听上下文：迈向忠实的大型语言模型，用于增强检索生成的气候问答

发布时间：2025年05月21日

`RAG` `气候科学` `大型语言模型`

> Listen to the Context: Towards Faithful Large Language Models for Retrieval Augmented Generation on Climate Questions

# 摘要

> 采用检索增强生成的大型语言模型，能够将冗长且技术性的气候相关文档变得更为易懂，从而为研究人员、政策制定者和公众释放出宝贵的知识。尽管这种方法通过检索到的段落作为额外上下文来缓解事实性幻觉，但其效果取决于模型输出是否忠实于这些段落。为此，我们研究了不同模型在这一场景下的忠实度自动评估方法。随后，我们聚焦于专注于气候科学的大型语言模型ClimateGPT，深入分析其指令微调过程中影响模型忠实度的关键因素。通过剔除训练数据中不忠实的部分，我们开发出了ClimateGPT Faithful+，其在支持的事实性声明中的忠实度，根据我们的自动指标，从30%显著提升至57%。

> Large language models that use retrieval augmented generation have the potential to unlock valuable knowledge for researchers, policymakers, and the public by making long and technical climate-related documents more accessible. While this approach can help alleviate factual hallucinations by relying on retrieved passages as additional context, its effectiveness depends on whether the model's output remains faithful to these passages. To address this, we explore the automatic assessment of faithfulness of different models in this setting. We then focus on ClimateGPT, a large language model specialised in climate science, to examine which factors in its instruction fine-tuning impact the model's faithfulness. By excluding unfaithful subsets of the model's training data, we develop ClimateGPT Faithful+, which achieves an improvement in faithfulness from 30% to 57% in supported atomic claims according to our automatic metric.

[Arxiv](https://arxiv.org/abs/2505.15633)